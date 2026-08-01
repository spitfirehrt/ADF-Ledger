# sealed/v1/ — integrity notes (append-only)

## 2026-07-26_claims.json — HASH DISCREPANCY (caught by the operator's skeptic drill)

The very first real seal (`TEST-2026-07-26-skeptic-drill`, one sacrificial TEST
claim) is **internally inconsistent** because of a byte-handling bug in the
pre-fix `seal.py`. **The skeptic drill worked: it caught this before any real
forecast was ever sealed.** The seal is left **byte-untouched** (append-only, no
re-seal, no re-stamp); this note is the honest record.

**Root cause.** Pre-fix `seal.py` computed the SHA-256 of the in-memory JSON
string (LF line endings) but wrote the file with Windows text-mode translation
(`write_text` -> LF becomes CRLF on disk). Compounded by the repo's
`core.autocrlf=true`, which normalised the working-tree CRLF back to LF when git
stored the blob. Result: **three** byte representations of the same claim data.

| representation | SHA-256 | where it lives |
|----------------|---------|----------------|
| **LF** | `1feb2b38ae9489922efe59275e3641513ffa7de684f62c18c87d5b43f477b924` | the git-stored blob, the `.sha256` sidecar, the drafted X-post, the operator reminder, AND a fresh `-text` checkout |
| **CRLF** | `9147602cfffc803ef7a0d65dfdf56be85ba9a3a5f290fe9c913e0e71b1cbe162` | the local working-tree file at seal time, AND **what the OpenTimestamps proof (`.ots`) attests** |

The OTS proof is valid — it correctly timestamps the exact on-disk (CRLF) bytes
that existed when `ots stamp` ran. Only the human-facing records (`.sha256`,
X-post, reminder) point at the LF hash, which `certutil` on the CRLF working-tree
file can never reproduce. That mismatch is what the drill surfaced.

**Do not "fix" this seal.** It stays as-is, as evidence the verification chain
has teeth. When citing it, note both hashes and that the `.sha256` sidecar
records the pre-fix LF value.

## The fix (applies to every seal AFTER 2026-07-26)

- `seal.py` now writes sealed files in **binary** (no LF->CRLF translation) and
  reads the SHA-256 back **from disk**, so the printed hash, the `.sha256` file,
  the OTS stamp, and the X-post all describe the same on-disk bytes on every OS.
- `.gitattributes` marks `sealed/**`, `graph/v*/**` as `-text` and `*.ots` as
  `binary`, so git never line-ending-rewrites a hashed artifact.
- `freeze.py` writes `wall.json` + `MANIFEST.sha256` in binary too (its per-file
  manifest hashes already read disk bytes, so tamper-detection was always sound).

A post-fix seal's `certutil -hashfile <sealed.json> SHA256` equals the hash
`seal.py` prints and records — verified on the re-drill claim
`TEST-2026-07-26-skeptic-drill-2`.
