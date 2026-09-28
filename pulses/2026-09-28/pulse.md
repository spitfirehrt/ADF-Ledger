# ADF PULSE — 2026-09-28

- epoch: v1  ·  run (UTC): `2026-09-28T05:47:24Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 1 active / 1 proposed  ·  0 resolved since last pulse  ·  8 assessed (3 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 33 | Taiwan monthly print ~2026-10-10 | rising · 58% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 33 | SK hynix Q3 earnings ~2026-10-24 | falling · 2% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 33 | Taiwan monthly print ~2026-10-10 | falling · 4% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 48 | Samsung Q3 preliminary guidance ~2026-10-08 | rising · 85% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 48 | Taiwan monthly print ~2026-10-10 | quiet · 88% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 63 | Taiwan monthly print ~2026-10-10 | quiet · 28% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 94 | Samsung Q3 preliminary guidance ~2026-10-08 | falling · 35% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 125 | Taiwan monthly print ~2026-10-10 | falling · 5% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **rising · 58%** (+6 pts vs last pulse, from 52%)
  - case: MediaTek newest smartphone chips explicitly on latest TSMC process (CBMiowFBVV95cUxPY1pjODFNQW0zNEJyYmFWdXQyY2swRHBSM0J5c2VNZl8xVmRLd0VIR0tCSGRzcEZJX25yd0M3OE5SdlZYWENtcmlGSzhsd1VyOUVRX1h1c1ZVMHR3Zl9HVG51WWVSVUl1SnFFWkNiMlNBX1k5WnBJbXk2clhLbTlxVkpXYnc2Z0RyS0NaSW9OdHF6SGVlMmxOa092cTNMMFg1YmJ3) plus NVDA–MediaTek $3.5b partnership expand the unwired TSM→MEDIATEK foundry pull into the Sept monthly pr
  - consensus: Street holds MEDIATEK 0q revenue growth near -2.45% with no modeled TSM leading-edge dependency.
  - deviation: STRENGTHENING — direct TSMC-node handset-SoC attribution and NVDA co-investment bias the upcoming Sept YoY print above the +5% confirm bar.
  - synthesis: Edge existence now evidenced; stand by for ~Oct 10 monthly with modest upward bias vs wall.
  - confidence: Prior 52 lifted by explicit TSMC-process MediaTek chip item and NVDA partnership; still no actual Sept print so capped.
  - evidence: `CBMiowFBVV95cUxPY1pjODFNQW0z`, `CBMiqAFBVV95cUxOMHY0NDVvckpp`

- `jobA-20260727T075315Z-C4` — **falling · 2%** (-2 pts vs last pulse, from 4%) **⚠ FLAGGED**
  - case: Multiple items state Micron guided to an 86% gross margin — far above the ≤55% confirm and the ≥60% fail line — so the commodity-DRAM/CXMT undershoot thesis is directly contradicted ahead of the Q4 print.
  - consensus: MU strong-buy with explosive HBM/AI revenue growth (+350% regime) and peak margins.
  - deviation: WEAKENING — 86% GM guide is the opposite of margin undershoot.
  - synthesis: GM≤55% short fully stood down; print far more likely to clear 60%.
  - confidence: Prior 4 cut further on explicit 86% GM guide items; only residual is guide-vs-actual risk.
  - evidence: `CBMimgFBVV95cUxQd0xlUnhTT1Ey`
  - ⚠ **alert** (low_confidence): confidence 2% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 4%** (-2 pts vs last pulse, from 6%) **⚠ FLAGGED**
  - case: BofA initiates Buy/$70 on AI surge, AI/HPC packaging demand-growth pieces, and Arizona packaging expansion all travel AMKR__TSM__adv_packaging_overflow and bias AMKR YoY well above the ≤15% confirm (and toward the 19.8% fail line).
  - consensus: AMKR unrated/~+20% 0q growth framed as AI/CoWoS overflow winner.
  - deviation: WEAKENING — overflow narrative reinforced; Apple-mix cap not evidenced this window.
  - synthesis: Do not lean ≤15%; live overflow edge still biases next print higher.
  - confidence: Prior 6 cut on BofA AI-surge initiate and repeated HPC packaging demand items with no Apple-seasonal counterweight.
  - evidence: `CBMikAFBVV95cUxNdG9CVlFJQWVv`, `CBMi4gFBVV95cUxOY0RzbFJFclF4`, `CBMi1wFBVV95cUxQREJkQXN3aldL`
  - ⚠ **alert** (low_confidence): confidence 4% <= 10%

- `QCOM-septq-rev-yoy-2026` — **rising · 85%** (+7 pts vs last pulse, from 78%)
  - case: Qualcomm official renewal of global patent license with Apple (multi-source, starting 2027) travels AAPL__QCOM__handset_modems and directly offsets the modem-insourcing decline narrative that underpins the -6.68% wall, lifting FYQ4 YoY odds above the confirm bar.
  - consensus: QCOM hold / 0q rev growth -10% framed as structural Apple-modem loser.
  - deviation: STRENGTHENING — long-term Apple patent/royalty bridge removes the core bear leg into the Sept-quarter print.
  - synthesis: Lean long QCOM into Nov FYQ4; patent renewal is the concrete offset the sealed thesis needed.
  - confidence: Prior 78 raised on primary-source Apple patent renewal across QTL; near-term stock chop and pure-licensing shift notes keep it under 90.
  - evidence: `CBMisAFBVV95cUxPMjhpU1pqVTYy`, `CBMiswFBVV95cUxQSVdvcW04c3BW`, `CBMingFBVV95cUxPX1JrSzJBVER5`, `CBMingFBVV95cUxOTkJfcnJrYVN4`

- `jobA-20260729T064012Z-C5` — **quiet · 88%** (-1 pts vs last pulse, from 89%)
  - case: Generic KLAC AI-infra and Singapore-expansion blurbs plus a weak TSM__KLA__process_control tag in a 1.4nm recap do not move the Sept-q ≥15% YoY observable; no TSMC process-control order or guide delta this window.
  - consensus: KLA buy / ~13.5% 0q growth, lowest conviction in the WFE group.
  - deviation: UNCHANGED — relative-rating gap vs AMAT/LRCX/ASML still the alpha, untested by new evidence.
  - synthesis: Sept-q ≥15% remains base case; no new pressure either way.
  - confidence: Prior 89 nudged down one tick on absence of hard TSMC-capex/KLA order confirmation this pulse.
  - evidence: `CBMizwFBVV95cUxQN01CZ1d3akI4`

- `jobA-20260726T115635Z-C4` — **quiet · 28%**
  - case: ASE $10.5B capex and machinery buys plus Lam AI-capex outlook items run in parallel; no disclosure ties LRCX tools into ASX advanced-packaging lines, so the missing edge and the LRCX ≥31% YoY observable stay unmoved.
  - consensus: Street prices LRCX +29% rev growth on broad WFE/AI with ASX as a separate OSAT AI beneficiary.
  - deviation: UNCHANGED — still no LRCX→ASX equipment supply evidence to justify a deviation.
  - synthesis: Remain stood down until a direct LRCX-ASX tool PO or disclosure appears.
  - confidence: Prior 28 held; ASX capex and LRCX analyst lifts are orthogonal, no mechanism bridge.

- `HBM-zerosum-skhynix-spread-2026` — **falling · 35%** (-9 pts vs last pulse, from 44%)
  - case: Jensen dual-meet with Lee and Chey on HBM/AI infra, joint Samsung–SK record Q3 profit prints, and Daishin dismissing SK HBM4 concerns all move SKHYNIX__NVDA__hbm and SAMSUNG__NVDA__hbm in the same direction; MU 86% GM guide further lifts the peer mean, pushing the SK–peer spread away from ≤-10%.
  - consensus: Memory cluster priced as uniform HBM/AI rally (all strong-buy, triple-digit growth).
  - deviation: WEAKENING — window evidence is co-operative allocation and simultaneous record profits, not zero-sum share shift.
  - synthesis: Relative underweight SKHYNIX into Dec spread loses support; mechanism untested and now biased against.
  - confidence: Prior 44 cut because dual CEO–Huang HBM meeting and record dual profits argue against SK underperformance.
  - evidence: `CBMidkFVX3lxTFA4MEROcWItbWs1`, `CBMinwFBVV95cUxPcUU5N3MtQ2pn`, `CBMidEFVX3lxTE5BU1B1NDVXRlU3`

- `AVGO-wafer-hike-multiple-2027` — **falling · 5%** (-2 pts vs last pulse, from 7%) **⚠ FLAGGED**
  - case: Digitimes locks TSMC 2027 wafer-out hikes at 3-6% (not 10%) on TSM__AVGO__foundry_wafers while Broadcom lifts 2026 AI semi revenue to $58B and re-affirms $350B outlook — cost-shock magnitude shrinks and demand narrative dominates the ≤480 multiple path.
  - consensus: AVGO strong-buy / ~$532 target with AI revenue compounding treated as strictly positive.
  - deviation: WEAKENING — realized hike print is 3-6% and AVGO guide-ups offset margin-compression thesis.
  - synthesis: Keep ≤480 short-multiple stood down; path of least resistance still higher into Jan-2027.
  - confidence: Prior 7 cut on 3-6% hike vs sealed 10% premise plus AVGO $58B AI raise; China audit risk only partial offset.
  - evidence: `CBMihgFBVV95cUxQMVE4Ty1hREZE`, `CBMiWEFVX3lxTE1kU2NHSWVXc0hI`, `CBMimwFBVV95cUxNNHlFU2JjMHNl`
  - ⚠ **alert** (low_confidence): confidence 5% <= 10%

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
- `SHK-TSM__AAPL__leading_edge_soc` TSM__AAPL__leading_edge_soc dir `+` (active)

**proposed shocks (await operator approval):**
- TSM__AAPL__leading_edge_soc dir `+` stress 16.8648

**propagation rows:**

| name | impact | lands | path |
|---|--:|:--:|---|
| AVGO | +0.2565 | 1 | TSM__AVGO__foundry_wafers |
| AMD | +0.2040 | 0 | TSM__AMD__leading_edge_wafers |
| NVDA | +0.2040 | 0 | TSM__NVDA__leading_edge_wafers |
| AMKR | +0.0805 | 1 | AAPL__AMKR__osat_packaging |
| ASML | +0.0612 | 2 | ASML__TSM__euv_systems |
| KLA | +0.0513 | 2 | TSM__KLA__process_control |

## §5 — RESOLUTIONS (since last pulse)

_no resolutions since the last pulse._

## §6 — CHECKPOINT OUTCOMES (since last pulse)

_Raw comparisons against the frozen reference. A comparison, **not a grade** — claims are graded only at resolution._

_no checkpoint passed since the last pulse._

---
_Tiers are stated: §1 is graded; §2/§3 are ungraded. Internal machinery (checkup evidence, amendment queue, stress-ledger internals, judge/repair rationales) never ships. Map changes reach buyers as epoch-boundary changelogs._
