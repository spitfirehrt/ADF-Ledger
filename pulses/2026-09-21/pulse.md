# ADF PULSE — 2026-09-21

- epoch: v1  ·  run (UTC): `2026-09-21T03:04:49Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 1 active / 3 proposed  ·  0 resolved since last pulse  ·  8 assessed (3 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 40 | Taiwan monthly print ~2026-10-10 | rising · 52% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 40 | MU fiscal-Q4 FY26 earnings ~2026-09-24 | falling · 4% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 40 | Taiwan monthly print ~2026-10-10 | falling · 6% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 55 | Samsung Q3 preliminary guidance ~2026-10-08 | rising · 78% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 55 | Taiwan monthly print ~2026-10-10 | rising · 89% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 70 | Taiwan monthly print ~2026-10-10 | quiet · 28% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 101 | MU fiscal-Q4 FY26 earnings ~2026-09-24 | rising · 44% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 132 | Taiwan monthly print ~2026-10-10 | falling · 7% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **rising · 52%** (+8 pts vs last pulse, from 44%)
  - case: TSMC Scores Another 2nm Win: MediaTek Dimensity 9600 Pro on N2P, plus TSM commercial 2nm start, wires the missing TSM→MEDIATEK leading-edge path and lifts odds the Sept monthly clears +5% YoY.
  - consensus: Street holds MEDIATEK 0q growth near -2.45% with no modeled TSM leading-edge dependency.
  - deviation: STRENGTHENING — explicit N2P design-win converts the unwired customer link into a near-term revenue mechanism.
  - synthesis: Hold for ~Oct 10 MediaTek Sept monthly; N2P win makes ≥+5% the base case vs the -2.45% fail bar.
  - confidence: Dimensity 9600 Pro N2P win raises confidence from 44; still capped because the sealed observable is one monthly print not yet released.
  - evidence: `CBMidkFVX3lxTE5lbFRyaW5wZmFK`, `CBMi7AFBVV95cUxNblhVN1A1bzdQ`

- `jobA-20260727T075315Z-C4` — **falling · 4%** (-1 pts vs last pulse, from 5%) **⚠ FLAGGED**
  - case: Micron warns shortages through 2027, Intel flags memory prices up 5–7x, and multi-year HBM contracts dominate — mix/price path pushes GM away from ≤55% toward the ≥60% fail bar along MU__NVDA__hbm.
  - consensus: Street frames MU as pure HBM-scarcity winner (strong_buy, ~350% rev growth).
  - deviation: WEAKENING — scarcity and contract evidence leave no room for the CXMT-commodity margin undershoot this window.
  - synthesis: Keep GM≤55% short fully stood down; Q4 print far more likely to clear 60% on HBM ramp mix.
  - confidence: Prior 5 edged lower on explicit 2027 shortage warning and 5–7x memory price print; no CXMT offset visible.
  - evidence: `CBMinwFBVV95cUxQZmZVMW51UVhW`, `CBMi0gFBVV95cUxQUkxKRzVYeW5l`, `CBMidkFVX3lxTE1ZdWdlY1NaTkNu`, `CBMipgFBVV95cUxPdnZSc0lsdGh3`
  - ⚠ **alert** (low_confidence): confidence 4% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 6%** (-2 pts vs last pulse, from 8%) **⚠ FLAGGED**
  - case: Amkor Phase-2 Arizona campus to $12B plus NVDA double-sales supply-chain piece activate AMKR__TSM__adv_packaging_overflow; AI packaging demand bias pushes next print away from ≤15% toward the ≥19.82% fail.
  - consensus: Street still shows AMKR 0q growth only ~2.7% with no rating, while AI-packaging narrative is the bull frame.
  - deviation: WEAKENING — Arizona Phase 2 and overflow tags make the AI-packaging leg dominant this window, against the Apple-seasonality cap thesis.
  - synthesis: Do not lean into ≤15%; overflow edge is live and Arizona Phase 2 biases the next print higher.
  - confidence: Prior 8 trimmed on Phase-2 $12B and explicit overflow tagging; Apple iPhone arrival is seasonal but does not offset the AI capacity signal.
  - evidence: `CBMimwFBVV95cUxPaXhMTmJQZDVS`, `CBMi3gFBVV95cUxQczBSZFE3Qi1r`, `CBMiugFBVV95cUxNcEhrWWVuaHRW`
  - ⚠ **alert** (low_confidence): confidence 6% <= 10%

- `QCOM-septq-rev-yoy-2026` — **rising · 78%** (+8 pts vs last pulse, from 70%)
  - case: Multiple independent teardowns (TechInsights X80, AppleInsider, 9to5Mac, MacRumors) confirm US iPhone 18 Pro Max still ships Qualcomm modem not Apple C2 — retained dollars travel AAPL__QCOM__handset_modems into the Sept-q YoY print.
  - consensus: Street holds QCOM as structural decliner (hold, 0q growth -10%) on Apple modem insourcing.
  - deviation: STRENGTHENING — teardown cluster falsifies near-term insourcing and anchors modem content through the sealed FYQ4 window.
  - synthesis: Lean long QCOM into Nov FYQ4; clearing -6.68% is now the clear base case on retained US modem dollars.
  - confidence: Teardown cluster lifts from 70; remaining risk is Samsung SoC timing and non-Apple handset softness inside the same quarter.
  - evidence: `CBMidkFVX3lxTE40LWVGZTNkSUVK`, `CBMijwFBVV95cUxOcmdtS1dMTVdS`, `CBMilAFBVV95cUxQM2pidDFMTi1q`, `CBMie0FVX3lxTE53WXU0Zkc3aXZZ`

- `jobA-20260729T064012Z-C5` — **rising · 89%** (+2 pts vs last pulse, from 87%)
  - case: TSM $31.4B expansion and 2nm ramp headlines explicitly tag TSM__KLA__process_control, while JPMorgan top-pick/AI-demand notes lift KLA — capex tailwind feeds the Sept-q ≥15% YoY bar.
  - consensus: Street still rates KLA only buy with the weakest equipment-group upside vs AMAT/LRCX/ASML strong_buys.
  - deviation: STRENGTHENING — TSM capex/N2 items raise the single-customer process-control path that the relative-rating gap still under-prices.
  - synthesis: Sept-q ≥15% remains base case; alpha is still the relative-rating gap vs AMAT/LRCX/ASML.
  - confidence: TSM $31.4B + 2nm items lift from 87; wall 0q growth already 26% makes ≥15% highly probable, residual risk only print timing.
  - evidence: `CBMilgFBVV95cUxNc0s4MlJseFJy`, `CBMi0wFBVV95cUxOcVhLTmc1cHJv`

- `jobA-20260726T115635Z-C4` — **quiet · 28%**
  - case: LRCX record results and India ₹10,000 Cr / $1–1.2bn plant headlines move the isolated LRCX node but contain zero ASX or advanced-packaging-tool order language, so the sealed LRCX→ASX edge stays unproven and the ≥31% YoY bar is untouched.
  - consensus: Street already prices LRCX strong_buy with ~53% 0q growth and AI WFE upside.
  - deviation: UNCHANGED — general AI/India capex noise does not validate the missing LRCX-ASX supply edge.
  - synthesis: No action; stand down until a direct LRCX-ASX equipment disclosure appears.
  - confidence: Unchanged from prior: still no edge-level evidence; record-results headlines do not move the sealed observable toward 31%.
  - evidence: `CBMi0wFBVV95cUxQUEZxcnVsZ3J1`

- `HBM-zerosum-skhynix-spread-2026` — **rising · 44%** (+3 pts vs last pulse, from 41%)
  - case: Samsung doubles HBM4 family output and unveils zHBM while shifting DDR5/SSD to outsourcing — share pressure travels MU__SKHYNIX__hbm_capacity and SAMSUNG__NVDA__hbm against SKH primary allocation even as NVDA volume doubles.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as a uniform HBM rally (all strong_buy, triple-digit growth).
  - deviation: STRENGTHENING — Samsung HBM4 2x and zHBM make the zero-sum share edge live, biasing SKH relative underperformance.
  - synthesis: Maintain modest relative underweight SKHYNIX into the Dec spread; HBM4 share shift is the mechanism.
  - confidence: Samsung HBM4 double and zHBM lift from 41; offset by SKH Indiana HBM fab build and NVDA 2x demand that lifts the whole cluster absolutely.
  - evidence: `CBMidkFVX3lxTE1sSlV6VGtobnps`, `CBMiiAFBVV95cUxPWlNUTk5nT09h`, `CBMipAFBVV95cUxPN0pGTm5INmw2`, `CBMidEFVX3lxTFBMZUVscTltc3BS`

- `AVGO-wafer-hike-multiple-2027` — **falling · 7%** (-2 pts vs last pulse, from 9%) **⚠ FLAGGED**
  - case: TSMC foundry price hikes ripple downstream (AMD 10% Q4 pass-through) while AVGO names Anthropic as next custom-silicon customer past Google along TSM__AVGO__foundry_wafers — demand/pass-through dominates the cost-shock multiple path to ≤480.
  - consensus: Street strong_buy AVGO with mean target ~532 and 94% rev growth, treating AI custom silicon as strictly positive.
  - deviation: WEAKENING — cost pass-through plus Anthropic win keep the multiple path higher, away from the ≤480 confirm.
  - synthesis: Keep the ≤480 short-multiple stood down into Jan-2027; path of least resistance remains higher.
  - confidence: Prior 9 trimmed on Anthropic customer win and AMD pass-through evidence that fabless can reprice rather than compress.
  - evidence: `CBMingFBVV95cUxOaG5MczVLdzlG`, `CBMidkFVX3lxTFBWYUd3cklUc0Jk`, `CBMibEFVX3lxTFBtN3czbjEzT0Va`
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

**active / approved shocks:**
- `SHK-AAPL` AAPL dir `+` (active)

**proposed shocks (await operator approval):**
- AAPL dir `+` stress 28.6014
- TSM__AAPL__leading_edge_soc dir `+` stress 24.6297
- AVGO__AAPL__wireless_content dir `+` stress 1.4739

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

_no resolutions since the last pulse._

## §6 — CHECKPOINT OUTCOMES (since last pulse)

_Raw comparisons against the frozen reference. A comparison, **not a grade** — claims are graded only at resolution._

_no checkpoint passed since the last pulse._

---
_Tiers are stated: §1 is graded; §2/§3 are ungraded. Internal machinery (checkup evidence, amendment queue, stress-ledger internals, judge/repair rationales) never ships. Map changes reach buyers as epoch-boundary changelogs._
