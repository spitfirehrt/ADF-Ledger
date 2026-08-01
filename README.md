# ADF Ledger — a pre-registered, timestamped forecast record

This repository is a **public, append-only record of specific predictions about
semiconductor-industry companies** — each one **sealed before its outcome was
known**, cryptographically hashed, and anchored to the Bitcoin blockchain so that
anyone can confirm *when* it was written. Predictions are graded **mechanically**
on a pre-committed rule, and both hits and misses are published the same day.

You do not have to trust us. **You can check it yourself in about 90 seconds.**
Every file here carries its own SHA-256 hash and an OpenTimestamps proof; the
steps below let a stranger confirm that a prediction existed, unchanged, before
the event it predicts.

> **What this is not:** not investment advice, not a recommendation, not a
> performance guarantee. It is a data record. See *What grading means* and
> *What is deliberately not here* below.

---

## What's in this repo

```
sealed/         the sealed predictions — one JSON file per sealing event,
                each with a .sha256 (its hash) and a .ots (its Bitcoin proof)
sealed/v1/      + README.md (an honesty note about a bug the first drill caught)
resolutions/    the graded verdicts, added on each prediction's resolution date
pulses/         the twice-weekly public snapshots (added as they ship)
PREHISTORY-LEDGER.md   the pre-launch record (see that file)
```

Two of the files in `sealed/v1/` are **TEST drills** (their claim ids start with
`TEST-…skeptic-drill`), not real forecasts — they exist because we sealed a
throwaway claim first to prove the machinery worked. They stay published, labeled,
as honest evidence. See `sealed/v1/README.md`.

---

## How to verify in 90 seconds

**The two things you're proving:** (1) a sealed file's bytes hash to exactly the
number recorded beside it — so nothing was altered after sealing; and (2) that
hash was written into a Bitcoin block at a specific time — so the file provably
existed **before** the outcome it predicts.

Pick any file in `sealed/v1/` **other than** `2026-07-26_claims.json` (that first
drill has a documented line-ending quirk — see the note at the end). A good
example is **`sealed/v1/2026-07-27_claims.json`**.

### (a) Read the expected hash
Open `sealed/v1/2026-07-27_claims.sha256` (click it on GitHub). It contains one
line — the SHA-256 the file should have:
`21c80846bea615618562885d96ec7796befead9b1eb77e068d079b731fe16d54`.

### (b) Recompute the hash yourself

**With a terminal:**
- **Windows:** `certutil -hashfile sealed\v1\2026-07-27_claims.json SHA256`
- **macOS:** `shasum -a 256 sealed/v1/2026-07-27_claims.json`
- **Linux:** `sha256sum sealed/v1/2026-07-27_claims.json`

**Without a terminal (browser only):** on GitHub, open the `.json` file → click
**Raw** → save it. Then drop that file into any "SHA-256 file" web tool (search
"sha256 file online"), or on GitHub the file's page shows a permalink whose commit
history proves it hasn't changed.

### (c) Confirm it matches
The number from step (b) must equal the number in step (a), character for
character. If it matches, the file is byte-for-byte what was sealed.

### (d) Check the Bitcoin timestamp
Each sealed `.json` has a `.ots` proof beside it (e.g.
`2026-07-27_claims.json.ots`). Go to **https://opentimestamps.org**, and in its
verify box drop in **both** the sealed `.json` and its `.ots` file. The page
reports the **Bitcoin block** the hash was anchored in and the **UTC time** of
that block.

> **UNVERIFIED (website wording):** we confirmed this proof locally with the
> OpenTimestamps client — it reports Bitcoin block **959856** for
> `2026-07-27_claims.json` — but we have not driven the opentimestamps.org web page
> from our side, so the exact words it displays are stated from the tool, not the
> site. If you have the `ots` client: `ots verify sealed/v1/2026-07-27_claims.json`.

### (e) Confirm the timestamp precedes the outcome
Open the sealed `.json` and read each claim's `observable.as_of_date` — its
**resolution date**. The Bitcoin block time from step (d) (late July 2026) is
**months earlier** than the earliest resolution date in this ledger (**2026-09-15**).
That gap is the whole point: the prediction was locked, provably, before anything
could be known.

---

## How to read a sealed claim

Each sealed `.json` holds one or more `claims`. In plain words:

- **`statement`** — the prediction, in a sentence.
- **`tag`** — either **`ALPHA`** (the prediction *disagrees* with the market
  consensus — the interesting case) or **`CONSENSUS-HOLDS`** (it *agrees* with
  consensus — a calibration check, not a contrarian call).
- **`observable`** — the exact, checkable quantity the prediction rides on:
  a **metric**, a **comparator** (`>=`, `<=`, …), a **threshold** number, a
  **unit**, the **source** the actual figure will come from, and the
  **`as_of_date`** (the resolution date).
- **`fails_if`** — the **pre-committed way to be wrong**, sealed at the same time.
  If this condition is met, the claim is a miss — no reinterpreting after the fact.
- **`window`** — how far out the prediction reaches, in quarters (`[1]` = the next
  quarter, `[2]` = two out).
- **`cited_wall`** — the consensus figure the prediction was measured against at
  seal time (so you can see exactly what it agreed or disagreed with).

There is a `.sha256` (the hash) and a `.ots` (the Bitcoin proof) beside every
sealed `.json`.

---

## What grading means

On a claim's resolution date, the real figure is fetched (or, for a few
manually-sourced figures, entered from the published print) and compared to the
sealed rule — **mechanically, no judgment:**

- **CONFIRM** — the observable was met.
- **DISCONFIRM** — the observable was not met, **or** the pre-committed `fails_if`
  condition fired.
- **UNRESOLVED** — the figure couldn't be obtained or the comparison was
  undecidable. It stays visible and counts toward neither a hit nor a miss, but it
  is reported, never hidden.

There is **no partial credit**, and the rule cannot be moved after sealing.
**Misses are published the same day, in the same format as hits** — the record is
symmetric by construction.

---

## What is deliberately NOT here (and why it doesn't affect verification)

This repo is **outputs only**. It does **not** contain the dependency graph, the
edge weights, the mechanisms, the model prompts, the reasoning, or any internal
deliberation — those stay private. That's by design: the value is a predictive
model, and the model is not for sale.

**This does not weaken verification.** Verification is about *whether a specific
prediction existed, unchanged, before its outcome* — which the hash + Bitcoin
timestamp prove completely, without anyone needing to see how the prediction was
made. You are checking the sealed claim, not the method behind it.

---

## Scoreboard (honest, today)

- **9 predictions** are sealed and open.
- **0** have resolved yet.
- The **first resolution date is 2026-09-15**.
- **No hit-rate or accuracy figure is claimed** — there is nothing to score until
  claims start resolving. When they do, every verdict (hit or miss) will be added
  here, same-day, in identical format.

*(This scoreboard is a snapshot. Re-read the files in `sealed/` and `resolutions/`
for the live state.)*

---

## Note on the first drill seal (`sealed/v1/2026-07-26_claims.json`)

The very first thing sealed was a throwaway TEST claim, on purpose — a dress
rehearsal. It surfaced a real byte-handling bug (a Windows line-ending translation)
**before any actual forecast was ever sealed**: its recorded `.sha256` is the LF
hash while the on-disk file is CRLF, so those two won't match on a naive check.
We left it exactly as-is as honest evidence that the verification chain has teeth,
and documented it fully in `sealed/v1/README.md`. Every seal **after** 2026-07-26
is byte-consistent (that's why the verification steps above use `2026-07-27`).
