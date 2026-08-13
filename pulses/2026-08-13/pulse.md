# ADF PULSE — 2026-08-13

- epoch: v1  ·  run (UTC): `2026-08-13T03:17:42Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **9 open sealed claim(s)** (8 ALPHA / 1 calibration)  ·  0 watch (1 retired)  ·  3 tracked  ·  shocks: 0 active / 0 proposed  ·  0 resolved since last pulse  ·  9 assessed (0 flagged)  ·  1 checkpoint outcome(s)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260727T075315Z-C8` | CONSENSUS-HOLDS · graded (shadow-rate) | TSM · TSM__NVDA__leading_edge_wafers,TSM__AVGO__foundry_wafers,TSM__AMD__leading_edge_wafers | TSM September-2026 monthly revenue print, YoY  [>= +40%] | [1] | evidence-accumulating | 33 | Taiwan monthly print ~2026-09-10 | rising · 72% |
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 79 | Taiwan monthly print ~2026-09-10 | quiet · 28% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 79 | MU pre-announcement window ~2026-09-10 | falling · 25% |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 79 | Taiwan monthly print ~2026-09-10 | falling · 30% |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 94 | Samsung Q3 preliminary guidance ~2026-10-08 | rising · 48% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 94 | Taiwan monthly print ~2026-09-10 | rising · 58% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 109 | Taiwan monthly print ~2026-09-10 | quiet · 30% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 140 | MU pre-announcement window ~2026-09-10 | falling · 28% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 171 | Taiwan monthly print ~2026-09-10 | falling · 32% |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260727T075315Z-C8` — **rising · 72%**
  - case: TSMC July revenue +44.7%/+45% to record NT$467.6B / $14.5B, driven by NVDA/AMD/AAPL AI demand along TSM__NVDA__leading_edge_wafers, TSM__AMD__leading_edge_wafers and TSM__AVGO__foundry_wafers, plus 98-99% CoWoS yields, keep the >=40% September YoY path intact; AAPL DRAM packaging holds are secondary.
  - consensus: Street already bakes +46.15% 0q growth and strong-buy on TSM leading-edge AI demand.
  - deviation: UNCHANGED (consensus-holds) — July prints sit squarely on the sealed >=40% track and reinforce rather than challenge the wall.
  - synthesis: July run-rate and CoWoS yield strength make a September YoY print >=40% the base case; claim remains the calibration anchor.
  - confidence: Consecutive ~45% July prints and explicit NVDA/AMD/AAPL demand raise confidence; residual DRAM-packaging drag and one-month gap to the September print keep it from the high 80s.
  - evidence: `CBMiowFBVV95cUxNdXIybklKY1k3`, `CBMidkFVX3lxTE1Ldll5bE9MdDlZ`, `CBMinAFBVV95cUxOMVYyNDVYMk0t`, `CBMiV0FVX3lxTE9reG8wSVVSeHBq`, `CBMilwFBVV95cUxNUjlCSVo2bWxB`

- `jobA-20260726T115635Z-C11` — **quiet · 28%**
  - case: Window telemetry is exclusively TSM July revenue (+45%), CoWoS yields and AAPL DRAM packaging holds; zero MediaTek monthly-revenue prints or TSM-MEDIATEK order flow appear, so the September YoY observable is unmoved.
  - consensus: Street holds MEDIATEK 0q revenue growth at -0.0245 with a buy rating and no wired TSM leading-edge edge.
  - deviation: UNCHANGED — claim posits an unwired TSM->MEDIATEK leading-edge edge, but nothing in this window tests or supports it.
  - synthesis: No evidence on the sealed MediaTek September print; treat the claimed edge as still unproven and do not act.
  - confidence: No MediaTek-specific telemetry and wall already embeds negative growth; only the distant as-of date keeps confidence off the floor.

- `jobA-20260727T075315Z-C4` — **falling · 25%**
  - case: Micron 'structural reset' in earnings power, HBM squeeze past 2027, and HBM4E custom-era items along MU__NVDA__hbm and MU__SKHYNIX__hbm_capacity all point to scarcity-driven margin expansion, opposite the commodity-DRAM/CXMT undershoot the claim needs; no CXMT supply evidence appears.
  - consensus: Street treats MU as pure HBM-scarcity winner (0q growth +349%, strong-buy).
  - deviation: WEAKENING — every MU item this window reinforces the HBM-scarcity margin narrative and supplies zero CXMT/commodity offset.
  - synthesis: Gross-margin <=55% looks less likely while HBM scarcity and structural-reset language dominate; claim needs commodity-DRAM evidence that is absent.
  - confidence: Uniform HBM-bullish MU telemetry and missing CXMT pressure sharply reduce odds the Q4 GM prints at or below 55%.
  - evidence: `CBMi9wFBVV95cUxQY2JFdG40b3hM`, `CBMidkFVX3lxTFBmbFROb010aWlf`, `CBMi4gFBVV95cUxNZGNYc0dma0tJ`

- `jobA-20260729T064012Z-C6` — **falling · 30%**
  - case: Amkor Q2 +26% revenue, AI-driven outlook, Nvidia packaging deal and margin-breakthrough items, plus TSMC CoWoS 98-99% yields and overflow tags on AMKR__TSM__adv_packaging_overflow, all push growth above the wall; no AAPL__AMKR__osat_packaging seasonal drag appears.
  - consensus: Street holds AMKR 0q growth at +19.82% buy, already embedding some AI packaging upside.
  - deviation: WEAKENING — printed +26% Q2 and NVDA packaging win show the CoWoS-overflow/AI book dominating, opposite the claim that Apple mix caps growth <=15%.
  - synthesis: AI/overflow strength is overpowering the Apple-cap thesis this window; claim's <=15% observable is moving away from confirmation.
  - confidence: Q2 +26% already above the fail threshold and NVDA deal raise the odds growth stays elevated; Apple-mix evidence would be required to reverse.
  - evidence: `CBMiigFBVV95cUxPZHc2TnN0Sm9y`, `CBMisAFBVV95cUxNSDFaLVdyS0xV`, `CBMilwFBVV95cUxPXzhsaWZwRUI3`, `CBMiogFBVV95cUxNRjBSVFl6VTdz`, `CBMiugFBVV95cUxPeVBUV2ZSUm5r`

- `QCOM-septq-rev-yoy-2026` — **rising · 48%**
  - case: Galaxy S26 FE Qualcomm-chip FCC filings and Snapdragon 8 Elite Gen 5 Galaxy AI extension travel along SAMSUNG__QCOM__handset_socs as incremental flagship content; offset by global SoC shipment -15% memory-crisis and 'largest revenue line shrinking' items on AAPL__QCOM__handset_modems.
  - consensus: Street frames QCOM as structural decliner (0q growth -6.68%, hold) on Apple modem insourcing.
  - deviation: STRENGTHENING — new Samsung flagship SoC design-win telemetry supplies the exact offset the claim names against the Apple drag.
  - synthesis: Samsung wins are live and directionally support Sept-q YoY > -6.68%; memory-driven handset weakness is the residual risk to the print.
  - confidence: Concrete S26 FE/Snapdragon wins raise odds of beating the wall, but SoC-shipment contraction and recent earnings miss cap conviction.
  - evidence: `CBMiwwFBVV95cUxNcGZCeXpfZG1E`, `CBMigAFBVV95cUxPd3JPbjFVbEJU`, `CBMidkFVX3lxTE15UEp3cENROGs3`, `CBMimgFBVV95cUxPMDJEQ1B0NU4w`, `CBMivAFBVV95cUxPS1NCUTZYZHZ5`

- `jobA-20260729T064012Z-C5` — **rising · 58%**
  - case: TSMC US$29.44B capex approval explicitly tagged to TSM__KLA__process_control (and peer WFE edges) plus equipment-stock reaction to TSM +45% revenue supply the single-customer N2/leading-edge tailwind; KLA's own Q4 beat/soft-guide item is the offset.
  - consensus: Street gives KLA the weakest equipment-group rating (buy) and only +13.49% 0q growth despite TSM concentration.
  - deviation: STRENGTHENING — TSM's large approved capex budget travels directly along the sealed TSM__KLA__process_control edge toward a >=15% YoY September quarter.
  - synthesis: TSM capex is live and sized to push KLA above the 15% threshold; soft near-term guide is the only brake.
  - confidence: Sized TSM capex directly on the KLA edge raises odds of clearing +15%, tempered by KLA's own soft-guide print and the still-modest spread over wall.
  - evidence: `CBMiV0FVX3lxTE5zbzlGYlkyZWlS`, `CBMiVEFVX3lxTE4zUGk0WUVWVVRI`, `CBMixwFBVV95cUxPU25YbGE2enJN`, `CBMie0FVX3lxTE5UakQtNk9veC1N`

- `jobA-20260726T115635Z-C4` — **quiet · 30%**
  - case: LRCX items cover panel-level packaging entry and AI-supercycle commentary; ASX items show July revenue strength and CoWoS-overflow via ASX__TSM__adv_packaging_overflow; no LRCX->ASX equipment-supply transmission is evidenced.
  - consensus: Street holds LRCX 0q revenue growth at +29% with a strong-buy rating; ASX is a separate OSAT name.
  - deviation: UNCHANGED — claimed LRCX-ASX advanced-packaging equipment edge remains fully unwired and untested this window.
  - synthesis: Parallel positive prints on LRCX and ASX do not create the missing supply edge; observable stays at consensus until an actual LRCX shipment or design-win link appears.
  - confidence: No direct LRCX-ASX link and the beat-to-+31% bar is tight against a +29% wall; time-to-resolution is the only support.

- `HBM-zerosum-skhynix-spread-2026` — **falling · 28%**
  - case: Samsung HBM4 yield to 80%, SK hynix $38B expansion + HBM4E samples, and Micron 'structural reset'/HBM-squeeze items all print as simultaneous positives along MU__SKHYNIX__hbm_capacity, SKHYNIX__NVDA__hbm and SAMSUNG__NVDA__hbm, showing shared scarcity not zero-sum share loss.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as a uniform HBM rally (strong-buy, elevated targets) with no built-in loser.
  - deviation: WEAKENING — every HBM supplier is receiving positive capacity/yield/demand telemetry, contradicting the claim that at least one must disappoint on the negative edge.
  - synthesis: Cluster-wide squeeze and dual expansion make SKHYNIX underperforming the MU-SAMSUNG mean by >=10% less likely; scarcity is lifting all three.
  - confidence: Uniform positive HBM prints across all three nodes and NVDA supply edges lower the odds of the required negative SKHYNIX spread.
  - evidence: `CBMiowFBVV95cUxQeDZMaUxtVkRy`, `CBMi9wFBVV95cUxQY2JFdG40b3hM`, `CBMiiwFBVV95cUxQdFRlY0syc1M2`, `CBMiYkFVX3lxTE10N25GcnpiVTND`, `CBMizwFBVV95cUxNVkpreHNBdFJU`

- `AVGO-wafer-hike-multiple-2027` — **falling · 32%**
  - case: Broadcom AI-chip sales +143% and $30B backlog item travels along TSM__AVGO__foundry_wafers as pure demand strength; TSM July +45% revenue and CoWoS yield prints reinforce the positive AI narrative with no wafer-price-hike or margin-compression mention.
  - consensus: Street has AVGO at strong-buy, target 525.44, 0q revenue growth +84.5%, treating TSMC supply as a pure positive.
  - deviation: WEAKENING — demand-side surge on the sealed edge is drowning the cost-shock thesis the claim needs for multiple compression.
  - synthesis: AVGO price (381.92) sits well below the <=480 confirm threshold but momentum and backlog make a hike-driven derating less probable; watch for explicit 2027 price commentary.
  - confidence: AI backlog strength and absence of any hike language lower odds the multiple compresses to the claim's threshold by Jan 2027.
  - evidence: `CBMilwFBVV95cUxQaHd4bnU2V0Fl`, `CBMiowFBVV95cUxNdXIybklKY1k3`, `CBMidkFVX3lxTE1Ldll5bE9MdDlZ`

## §2 — WATCH (warming up)

_Ungraded; promotion-before-resolution only._

_no active watches._

**retired since the last pulse:**

- **W1-cowos-overflow-amkr-asx** [`confirmed-absorbed`] — RETIRED 2026-08-10 (ungraded; no scoreboard credit)
  - ASE Jul-30 guidance raise to 35% ATM growth + Jun/Jul monthly prints confirmed the overflow thesis publicly before the Aug-10 activation test; operator declined promotion at the 08-06 and 08-10 gates — same-direction claim would be consensus-echo. Vindicated, unscored.

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

- **2026-08-10** — ASE (ASX) Taiwan monthly revenue print, YoY, breaks materially above the CoWoS-overflow baseline (a T1/T2 filing/print corroborating the overflow going live) (`W1-cowos-overflow-amkr-asx`)
  - printed: **+36.4% (USD YoY), +49.5% (NT$ YoY)**  ·  frozen reference: 25.4% frozen track
  - **W1 activation test PASSED**
  - source: operator-entry

---
_Tiers are stated: §1 is graded; §2/§3 are ungraded. Internal machinery (checkup evidence, amendment queue, stress-ledger internals, judge/repair rationales) never ships. Map changes reach buyers as epoch-boundary changelogs._
