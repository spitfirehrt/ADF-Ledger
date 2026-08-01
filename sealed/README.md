# sealed/ — APPEND-ONLY (CLAUDE.md rule 2)

Sealed claim sets: `sealed/<epoch>/<date>_claims.json` + `.sha256` (+ `.ots` proof).
Written only by `tools/seal.py`. New files only — never edit or delete a sealed
file. `seal.py` refuses to overwrite an existing seal.
