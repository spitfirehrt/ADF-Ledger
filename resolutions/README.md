# resolutions/ — APPEND-ONLY (CLAUDE.md rule 2)

Per-claim actuals + resolutions:
- `<claim_id>_actuals.json` — fetched by `tools/fetch_actuals.py` (re-fetchable cache).
- `<claim_id>_manual.json` — operator-entered actuals (manual/EDGAR sources).
- `<claim_id>_resolution.json` — the mechanical verdict from `tools/match.py`
  (CONFIRM/DISCONFIRM/UNRESOLVED). Append-only: `match.py` refuses to overwrite.
