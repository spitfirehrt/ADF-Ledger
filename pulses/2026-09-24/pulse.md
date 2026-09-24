# ADF PULSE — 2026-09-24

- epoch: v1  ·  run (UTC): `2026-09-24T08:48:14Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 2 proposed  ·  0 resolved since last pulse  ·  8 assessed (3 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 37 | Taiwan monthly print ~2026-10-10 | quiet · 52% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 37 | SK hynix Q3 earnings ~2026-10-24 | quiet · 4% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 37 | Taiwan monthly print ~2026-10-10 | quiet · 6% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 52 | Samsung Q3 preliminary guidance ~2026-10-08 | quiet · 78% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 52 | Taiwan monthly print ~2026-10-10 | quiet · 89% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 67 | Taiwan monthly print ~2026-10-10 | quiet · 28% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 98 | Samsung Q3 preliminary guidance ~2026-10-08 | quiet · 44% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 129 | Taiwan monthly print ~2026-10-10 | quiet · 7% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **quiet · 52%**
  - case: No tagged items landed on TSM or MEDIATEK this window; nothing moved the September-2026 MediaTek YoY revenue observable.
  - consensus: Street holds MediaTek near-term revenue growth soft-to-negative (cited wall -2.45%).
  - deviation: UNCHANGED this window — no monthly print or leading-edge demand evidence arrived to test the ≥+5% deviation.
  - synthesis: Stand by for ~Oct 10 MediaTek Sept monthly; prior N2P base case intact but untested.
  - confidence: Unchanged from prior: no new evidence to raise or lower the hold-for-Oct-10 print.

- `jobA-20260727T075315Z-C4` — **quiet · 4%** **⚠ FLAGGED**
  - case: No tagged items on MU; nothing moved the fiscal Q4 FY2026 GAAP gross-margin observable toward ≤55%.
  - consensus: Street frames MU as HBM-scarcity winner with extreme rev growth (~3.5x) baked in.
  - deviation: UNCHANGED — no CXMT/commodity-DRAM margin evidence this window.
  - synthesis: Keep GM≤55% short fully stood down; Q4 print still more likely to clear 60% on HBM mix.
  - confidence: Unchanged: empty window gives no lift to the already near-zero short case.
  - ⚠ **alert** (low_confidence): confidence 4% <= 10%

- `jobA-20260729T064012Z-C6` — **quiet · 6%** **⚠ FLAGGED**
  - case: No tagged items on AMKR or AAPL; neither AAPL__AMKR__osat_packaging nor AMKR__TSM__adv_packaging_overflow moved the AMKR rev-YoY ≤15% observable.
  - consensus: Street frames AMKR with ~20% rev growth (cited 0.1982) as CoWoS-overflow AI packaging beneficiary.
  - deviation: UNCHANGED — no Apple packaging or overflow disclosure this window.
  - synthesis: Do not lean into ≤15%; overflow edge still live and biases next print higher.
  - confidence: Unchanged: empty window leaves the low-confidence short case stood down.
  - ⚠ **alert** (low_confidence): confidence 6% <= 10%

- `QCOM-septq-rev-yoy-2026` — **quiet · 78%**
  - case: No tagged items on QCOM; neither SAMSUNG__QCOM__handset_socs nor AAPL__QCOM__handset_modems carried new flow into the Sept-q rev YoY observable.
  - consensus: Street frames QCOM as structural decliner (hold, rev growth ~-10% wall / cited -6.68%).
  - deviation: UNCHANGED — no handset SoC/modem demand print this window to strengthen or weaken the beat-of--6.68% case.
  - synthesis: Lean long QCOM into Nov FYQ4 still the base case, but unreinforced this pulse.
  - confidence: Unchanged: high prior rests on retained modem dollars; no contrary or confirming item arrived.

- `jobA-20260729T064012Z-C5` — **quiet · 89%**
  - case: No tagged items on KLA or TSM; TSM__KLA__process_control carried no new N2/capex flow into the Sept-q rev YoY ≥15% observable.
  - consensus: Street gives KLA the weakest equipment-group rating/upside despite TSM concentration (wall growth ~0.26, cited 0.1349).
  - deviation: UNCHANGED — no quarter print or TSM capex item to move the ≥15% deviation.
  - synthesis: Sept-q ≥15% remains base case; alpha still the relative-rating gap vs AMAT/LRCX/ASML.
  - confidence: Unchanged: high prior untested but also uncontradicted by empty window.

- `jobA-20260726T115635Z-C4` — **quiet · 28%**
  - case: No tagged items on LRCX or ASX; no equipment-supply disclosure moved the LRCX rev-YoY observable.
  - consensus: Street prices LRCX latest-quarter rev growth around +29% (wall 0.528 longer-term; cited 0.29 bar).
  - deviation: UNCHANGED — still no direct LRCX–ASX advanced-packaging equipment link in evidence.
  - synthesis: Keep stood down until a direct LRCX-ASX equipment disclosure appears.
  - confidence: Unchanged: empty window supplies no reason to move the low prior.

- `HBM-zerosum-skhynix-spread-2026` — **quiet · 44%**
  - case: No tagged items on MU, SKHYNIX, or SAMSUNG; MU__SKHYNIX__hbm_capacity zero-sum edge did not move the Dec-31 spread observable.
  - consensus: Street prices the memory cluster as uniform strong-buy rallies (MU/SKHYNIX/SAMSUNG all elevated targets).
  - deviation: UNCHANGED — no HBM allocation or share-shift evidence to test relative underperformance of SKHYNIX.
  - synthesis: Maintain modest relative underweight SKHYNIX into the Dec spread; mechanism untested this window.
  - confidence: Unchanged: empty board leaves prior modest confidence intact.

- `AVGO-wafer-hike-multiple-2027` — **quiet · 7%** **⚠ FLAGGED**
  - case: No tagged items on AVGO or TSM; wafer-hike cost-shock path along TSM__AVGO__foundry_wafers did not move AVGO price toward ≤480.
  - consensus: Street is strong-buy AVGO with mean target ~532 and AI-demand framed as strictly positive.
  - deviation: UNCHANGED — no price or margin evidence this window on the 2027 hike multiple.
  - synthesis: Keep ≤480 short-multiple stood down into Jan-2027; path of least resistance still higher.
  - confidence: Unchanged: no tape or cost-pass-through item to alter the very low prior.
  - ⚠ **alert** (low_confidence): confidence 7% <= 10%

## §2 — WATCH (warming up)

_Ungraded; promotion-before-resolution only._

_no active watches._

## §3 — TRACKED (inventory)

_Ungraded, tracked for transparency._
- `jobA-20260727T075315Z-C5` — Equipment cluster priced idiosyncratically strong_buy but is one correlated 2Q-lagged capex bet.
- `jobA-20260727T075315Z-C6` — AAPL inverted target reads ex-growth, missing a TSM-locked refresh + Broadcom content lock (frame inversion).
- `jobA-20260729T064012Z-C12` — AAPL priced ex-growth (PT 318.8 < price 333, only large-cap set to fall); an M5 Mac/iPhone hardware upcycle on TSM N2 sole-source plus refreshed Broadcom connectivity content.

## §4 — SHOCKS & EXPOSURES

**proposed shocks (await operator approval):**
- AAPL dir `+` stress 20.2242
- TSM__AAPL__leading_edge_soc dir `+` stress 17.4158

## §5 — RESOLUTIONS (since last pulse)

_no resolutions since the last pulse._

## §6 — CHECKPOINT OUTCOMES (since last pulse)

_Raw comparisons against the frozen reference. A comparison, **not a grade** — claims are graded only at resolution._

_no checkpoint passed since the last pulse._

---
_Tiers are stated: §1 is graded; §2/§3 are ungraded. Internal machinery (checkup evidence, amendment queue, stress-ledger internals, judge/repair rationales) never ships. Map changes reach buyers as epoch-boundary changelogs._
