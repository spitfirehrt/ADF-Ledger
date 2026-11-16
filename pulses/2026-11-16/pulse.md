# ADF PULSE — 2026-11-16

- epoch: v1  ·  run (UTC): `2026-11-16T16:05:48Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **5 open sealed claim(s)** (5 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 1 active / 2 proposed  ·  3 resolved since last pulse  ·  5 assessed (2 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | -1 | — | falling · 8% **!** |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | -1 | — | rising · 96% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 14 | — | quiet · 14% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 45 | — | falling · 36% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 76 | Taiwan monthly print ~2026-12-10 | falling · 4% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `QCOM-septq-rev-yoy-2026` — **falling · 8%** (-4 pts vs last pulse, from 12%) **⚠ FLAGGED**
  - case: Bernstein ‘lousy margin outlook’ plus handset-revenue downgrade pieces on AAPL__QCOM__handset_modems and SAMSUNG__QCOM__handset_socs; wall 0q growth already -11.7% sits below the >-6.7% confirm line and near fails_if.
  - consensus: Street holds QCOM at hold with 0q revenue growth ~-11.7% as a structural handset decliner.
  - deviation: WEAKENING — downgrade tape and wall revision deepen the decline frame; no Samsung-SoC or price-hike offset printed.
  - synthesis: Cut conviction further on >-6.7% Sept-Q; with as_of 2026-11-15 immediate, print risk is skewed to the fails_if side.
  - confidence: Prior 12 cut on handset downgrade salience and wall growth already under the confirm threshold with resolution days away.
  - evidence: `CBMiqgFBVV95cUxOZFJCTnl6dm5O`, `CBMixAFBVV95cUxNbkZydE5NRjFF`
  - ⚠ **alert** (low_confidence): confidence 8% <= 10%

- `jobA-20260729T064012Z-C5` — **rising · 96%** (+1 pts vs last pulse, from 95%)
  - case: KLA Q1 revenue beat with stronger outlook directly supports Sept-2026 YoY >=0.15 on TSM__KLA__process_control; wall 0q growth ~0.43 already clears the sealed threshold.
  - consensus: Street rates KLA only buy (weakest equipment rating) with mean target implying modest upside vs peers’ strong_buy.
  - deviation: STRENGTHENING — beat-and-outlook print validates the TSM-concentration revenue tailwind the rating still under-prices.
  - synthesis: Treat >=15% Sept-Q as confirmed; residual alpha is rating/multiple catch-up, not the revenue test.
  - confidence: Prior 95 held and nudged on explicit Q1 beat/stronger-outlook item plus wall growth far above 0.15 with as_of immediate.
  - evidence: `CBMixwFBVV95cUxOQVF0NXY0WUc2`

- `jobA-20260726T115635Z-C4` — **quiet · 14%**
  - case: Window LRCX items are IBM sub-1nm collab, Enschede PLD facility, export-reg comments and sector slides; ASX item is NT$705M facility engineering — none establish an LRCX→ASX advanced-packaging equipment supply path or move LRCX.rev_yoy vs 0.31.
  - consensus: Street has LRCX at strong_buy with 0q revenue growth ~0.62 and no priced LRCX–ASX packaging-tool edge.
  - deviation: UNCHANGED — claimed edge remains off-board and unlinked to the sealed revenue observable this window.
  - synthesis: Remain stood down on any LRCX–ASX edge trade; observable still unlinked to the claimed mechanism.
  - confidence: Prior 14 held: no rev_yoy print and no ASX-directed tool order to justify a move.

- `HBM-zerosum-skhynix-spread-2026` — **falling · 36%** (-19 pts vs last pulse, from 55%)
  - case: SK hynix locks 50%+ of 2027-28 HBM4 capacity and doubles Nvidia-related sales while Micron pauses its $4.5B Taiwan HBM plant along MU__SKHYNIX__hbm_capacity — zero-sum share runs toward SKHYNIX outperformance, opposite of spread <= -0.1.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as a uniform AI-HBM rally (all strong_buy, triple-digit growth).
  - deviation: WEAKENING — capacity lock and MU plant pause show SKHYNIX taking share, not the underperformance the spread needs.
  - synthesis: Further dial back the SKHYNIX-underperform lean; window is SKHYNIX wallet extension versus MU pause, not SKHYNIX disappointment.
  - confidence: Prior 55 cut on HBM4 50%+ lock plus MU Taiwan pause, both push relative SKHYNIX total return the wrong way for <= -0.1.
  - evidence: `CBMihAFBVV95cUxQNlRxRk9WMU4z`, `CBMihgFBVV95cUxPTFV6em13cGpI`, `CBMidkFVX3lxTE1XdGcyRHZYMWIy`, `CBMidkFVX3lxTE5MR3BXRFFBNHBp`, `CBMigwFBVV95cUxPdjQtZWc0WE1n`

- `AVGO-wafer-hike-multiple-2027` — **falling · 4%** (+2 pts vs last pulse, from 2%) **⚠ FLAGGED**
  - case: Broadcom guides AI chip revenue to double to $115B in 2027 on TSM__AVGO__foundry_wafers; Huang-exit rotation into AVGO/TSMC is AI-content bid, not 10% wafer-cost multiple compression toward <=480.
  - consensus: Street is strong_buy AVGO with mean target ~528 and treats TSMC supply as pure AI volume tailwind.
  - deviation: WEAKENING — live tape is AI-revenue doubling and foundry-capacity expansion, opposite of margin-shock compression.
  - synthesis: Keep the Jan-2027 <=480 short stood down; transmission is AI content growth, not wafer-hike multiple crush.
  - confidence: Prior 2 nudged only slightly: bullish $115B AI guide and rotation raise the bar for a sub-480 close by Jan-2027.
  - evidence: `CBMi3wFBVV95cUxNU3hIbnVLdlY5`, `CBMidkFVX3lxTFBLM1BDM3NTQUFK`, `CBMiugFBVV95cUxQZWxweEhscUdZ`
  - ⚠ **alert** (low_confidence): confidence 4% <= 10%

## §2 — WATCH (warming up)

_Ungraded; promotion-before-resolution only._

_no active watches._

## §3 — TRACKED (inventory)

_Ungraded, tracked for transparency._
- `jobA-20260727T075315Z-C5` — Equipment cluster priced idiosyncratically strong_buy but is one correlated 2Q-lagged capex bet.
- `jobA-20260727T075315Z-C6` — AAPL inverted target reads ex-growth, missing a TSM-locked refresh + Broadcom content lock (frame inversion).
- `jobA-20260729T064012Z-C12` — AAPL priced ex-growth (PT 318.8 < price 333, only large-cap set to fall); an M5 Mac/iPhone hardware upcycle on TSM N2 sole-source plus refreshed Broadcom connectivity content.

## §4 — SHOCKS & EXPOSURES

**active / approved shocks:**
- `SHK-AAPL` AAPL dir `+` (active)

**proposed shocks (await operator approval):**
- AAPL dir `+` stress 12.2626
- TSM__AAPL__leading_edge_soc dir `+` stress 6.9785

**propagation rows:**

| name | impact | lands | path |
|---|--:|:--:|---|
| AMKR | +0.0805 | 1 | AAPL__AMKR__osat_packaging |
| TSM | +0.0408 | 0 | TSM__AAPL__leading_edge_soc |
| AVGO | +0.0360 | 1 | AVGO__AAPL__wireless_content |
| QCOM | +0.0255 | 1 | AAPL__QCOM__handset_modems |
| AVGO | +0.0174 | 1 | TSM__AAPL__leading_edge_soc → TSM__AVGO__foundry_wafers |
| AMD | +0.0139 | 0 | TSM__AAPL__leading_edge_soc → TSM__AMD__leading_edge_wafers |

## §5 — RESOLUTIONS (since last pulse)
- `jobA-20260726T115635Z-C11`: **DISCONFIRM** — observable not met (as of 2026-10-31; res-sha 90a226b0e51f7d9f)
- `jobA-20260727T075315Z-C4`: **DISCONFIRM** — fails_if fired (pre-committed disconfirmation met) (as of 2026-10-31; res-sha 56f889271ae72ff5)
- `jobA-20260729T064012Z-C6`: **DISCONFIRM** — fails_if fired (pre-committed disconfirmation met) (as of 2026-10-31; res-sha ab59bed5f710d299)

## §6 — CHECKPOINT OUTCOMES (since last pulse)

_Raw comparisons against the frozen reference. A comparison, **not a grade** — claims are graded only at resolution._

_no checkpoint passed since the last pulse._

---
_Tiers are stated: §1 is graded; §2/§3 are ungraded. Internal machinery (checkup evidence, amendment queue, stress-ledger internals, judge/repair rationales) never ships. Map changes reach buyers as epoch-boundary changelogs._
