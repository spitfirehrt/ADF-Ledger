# ADF PULSE — 2026-10-12

- epoch: v1  ·  run (UTC): `2026-10-12T05:28:26Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 0 proposed  ·  0 resolved since last pulse  ·  8 assessed (3 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 19 | TSM Q3 FY26 earnings ~2026-10-15 | quiet · 56% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 19 | SK hynix Q3 earnings ~2026-10-24 | falling · 1% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 19 | TSM Q3 FY26 earnings ~2026-10-15 | falling · 2% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 34 | QCOM fiscal-Q4 FY26 earnings ~2026-11-05 | quiet · 68% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 34 | TSM Q3 FY26 earnings ~2026-10-15 | rising · 87% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 49 | LRCX Sept-quarter earnings ~2026-10-22 | quiet · 28% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 80 | SK hynix Q3 earnings ~2026-10-24 | rising · 62% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 111 | TSM Q3 FY26 earnings ~2026-10-15 | falling · 3% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **quiet · 56%**
  - case: Window is pure TSMC Q3/September record-revenue prints (NT$1.49T, +50-54% Y/Y); zero MediaTek September monthly revenue items, so the sealed YoY observable is untouched.
  - consensus: Street holds MEDIATEK 0q revenue growth at -0.0245 with strong_buy rating.
  - deviation: UNCHANGED — no MediaTek print arrived to test the >=5% deviation.
  - synthesis: Stand by for the ~Oct 10 MediaTek Taiwan monthly; nothing in this window moves the claim.
  - confidence: No new information on the actual_key; prior 56 stands pending the sealed release date.

- `jobA-20260727T075315Z-C4` — **falling · 1%** **⚠ FLAGGED**
  - case: Window is wall-to-wall AI-memory price/profit surge and Samsung/SK Hynix/MU HBM capacity lock-ups; no CXMT commodity-DRAM margin pressure appears, and prior already flagged the GM observable resolved against <=55%.
  - consensus: Street treats MU as pure HBM-scarcity winner (rev growth +352%, strong_buy).
  - deviation: WEAKENING — every tagged item reinforces scarcity pricing, opposite the commodity-DRAM undershoot thesis.
  - synthesis: GM≤55% short fully retired; observable has resolved against the claim.
  - confidence: Prior 1 unchanged; no contrary GM evidence and memory supercycle headlines only confirm the miss.
  - evidence: `CBMidkFVX3lxTFB1NmpJV0tiNE9l`
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 2%** **⚠ FLAGGED**
  - case: TSMC-GlobalFoundries $2B US silicon-interposer/CoWoS deal tags AMKR__TSM__adv_packaging_overflow yet routes capacity to GF, not AMKR; AMKR price -3.7% vs ASX peers +2.6% already prices the Apple-mix cap the claim needs, but AI-packaging narrative still sits above the fail threshold.
  - consensus: Street still frames AMKR as CoWoS-overflow AI packaging name (target 76 vs 49).
  - deviation: WEAKENING — GF interposer win and peer divergence show overflow not accruing to AMKR; Apple book remains the governor.
  - synthesis: Do not lean ≤15%; AI narrative and prior prints already sit above the fail threshold.
  - confidence: Prior 2 held; GF deal and price divergence add no path to <=15% and keep confidence near floor.
  - evidence: `CBMigwJBVV95cUxOQlpVMmk3OHdI`, `price_anomaly:AMKR:2026-10-1`
  - ⚠ **alert** (low_confidence): confidence 2% <= 10%

- `QCOM-septq-rev-yoy-2026` — **quiet · 68%** (-2 pts vs last pulse, from 70%)
  - case: Apple iPhone 18 Pro component-order cuts travel AAPL__QCOM__handset_modems negative; offsetting Samsung Galaxy S27 Ultra 'Qualcomm-only' tip travels SAMSUNG__QCOM__handset_socs positive; net no clear move on the sealed Sept-q YoY.
  - consensus: Street frames QCOM as structural decliner (0q growth -10%, hold) on Apple modem loss.
  - deviation: UNCHANGED — Apple cut and Samsung win headlines cancel; still waiting on the FYQ4 print.
  - synthesis: Hold the >-6.7% long into Nov FYQ4; still waiting on the actual print, not the patent/order headlines.
  - confidence: Prior 70 nudged down slightly on Apple order-cut salience; Samsung SoC exclusive tip keeps the offset alive.
  - evidence: `CBMi2AFBVV95cUxPZkJIZFpPNTNB`

- `jobA-20260729T064012Z-C5` — **rising · 87%** (-1 pts vs last pulse, from 88%)
  - case: TSMC $64B capex still-may-not-be-enough piece explicitly tags TSM__KLA__process_control; KLA raised-2027-guidance note offsets the Morgan Stanley target cut, keeping Sept-q >=15% path intact.
  - consensus: Street gives KLA the weakest equipment rating (buy, target 233, 0q growth +26%) despite TSMC concentration.
  - deviation: STRENGTHENING — incremental TSMC capex commentary supports the under-priced N2/process-control tailwind.
  - synthesis: Sept-q ≥15% remains base case with incremental TSM-capex support; hold the long.
  - confidence: Prior 88 essentially held; MS target cut is noise against raised guidance and TSMC capex link.
  - evidence: `CBMipwFBVV95cUxPRWxLRDFYaXJI`, `CBMilgFBVV95cUxQVnBVMzBqT2Vh`, `CBMi3AFBVV95cUxNTVZ3M0IxSHBD`

- `jobA-20260726T115635Z-C4` — **quiet · 28%**
  - case: LRCX items cover Korea chamber milestone/support-revenue jump and NAND; ASX items cover facility buys and CoWoS overflow chatter; no LRCX-ASX tool disclosure or LRCX rev-YoY print that tests >=31%.
  - consensus: Street holds LRCX 0q revenue growth at +52.77% / +29% cited, strong_buy.
  - deviation: UNCHANGED — still no direct advanced-packaging supply link or quarterly actual.
  - synthesis: Remain stood down until a direct LRCX-ASX tool disclosure; observable still untested.
  - confidence: Prior 28 unchanged; evidence stays off the sealed LRCX.rev_yoy metric.

- `HBM-zerosum-skhynix-spread-2026` — **rising · 62%** (+7 pts vs last pulse, from 55%)
  - case: Samsung locks 75-80% of next-year memory output in long-term deals and passes Nvidia HBM4E quals -> SAMSUNG__NVDA__hbm and MU__SKHYNIX__hbm_capacity, tightening the shared pool against SK hynix even as SK hynix starts HBM4 volume.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as uniform HBM rally (all strong_buy, triple-digit growth).
  - deviation: STRENGTHENING — Samsung capacity lock-up is the live zero-sum mechanism the claim needs.
  - synthesis: Lean the <=-10% SKHYNIX-vs-peers spread short; Samsung share grab is now the live mechanism.
  - confidence: Prior 55 raised on multiple independent Samsung 80% lock-up prints plus HBM4E Nvidia pass; still two months of price path risk.
  - evidence: `CBMidkFVX3lxTFB1NmpJV0tiNE9l`, `CBMiVEFVX3lxTFBBWmdYUGs5R0FC`, `CBMiqAFBVV95cUxQaU5ub2hONTJH`, `CBMi2gFBVV95cUxNM2R4bkx4T3FP`, `CBMid0FVX3lxTFB5LUVpV1AxVER5`

- `AVGO-wafer-hike-multiple-2027` — **falling · 3%** **⚠ FLAGGED**
  - case: AVGO $50B OpenAI/Anthropic chip-financing headlines travel TSM__AVGO__foundry_wafers as pure demand tailwind; TSMC record AI revenue reinforces the positive narrative the claim says should be margin-negative, pushing AVGO price further from <=480.
  - consensus: Street AVGO strong_buy, target_mean ~531, price 361, 0q rev growth +93%.
  - deviation: WEAKENING — financing and TSMC AI prints keep multiple-expansion path live into 2027.
  - synthesis: Keep ≤480 short-multiple stood down; path of least resistance still higher into Jan-2027.
  - confidence: Prior 3 held; OpenAI funding and TSMC beat add no cost-shock evidence and raise the bar to hit <=480.
  - evidence: `CBMizgFBVV95cUxObU9Wc2xwM1A2`, `CBMiqwFBVV95cUxPUlI5SWlmSHJf`
  - ⚠ **alert** (low_confidence): confidence 3% <= 10%

## §2 — WATCH (warming up)

_Ungraded; promotion-before-resolution only._

_no active watches._

## §3 — TRACKED (inventory)

_Ungraded, tracked for transparency._
- `jobA-20260727T075315Z-C5` — Equipment cluster priced idiosyncratically strong_buy but is one correlated 2Q-lagged capex bet.
- `jobA-20260727T075315Z-C6` — AAPL inverted target reads ex-growth, missing a TSM-locked refresh + Broadcom content lock (frame inversion).
- `jobA-20260729T064012Z-C12` — AAPL priced ex-growth (PT 318.8 < price 333, only large-cap set to fall); an M5 Mac/iPhone hardware upcycle on TSM N2 sole-source plus refreshed Broadcom connectivity content.

## §4 — SHOCKS & EXPOSURES

**board quiet — zero shocks.** The map sees no structural change; recent moves read as flow, not dependency stress.

## §5 — RESOLUTIONS (since last pulse)

_no resolutions since the last pulse._

## §6 — CHECKPOINT OUTCOMES (since last pulse)

_Raw comparisons against the frozen reference. A comparison, **not a grade** — claims are graded only at resolution._

_no checkpoint passed since the last pulse._

---
_Tiers are stated: §1 is graded; §2/§3 are ungraded. Internal machinery (checkup evidence, amendment queue, stress-ledger internals, judge/repair rationales) never ships. Map changes reach buyers as epoch-boundary changelogs._
