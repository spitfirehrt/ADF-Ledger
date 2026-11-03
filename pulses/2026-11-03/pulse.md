# ADF PULSE — 2026-11-03

- epoch: v1  ·  run (UTC): `2026-11-03T08:15:53Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 1 active / 2 proposed  ·  0 resolved since last pulse  ·  8 assessed (2 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | -3 | — | quiet · 58% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | -3 | — | falling · 1% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | -3 | — | rising · 42% |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 12 | QCOM fiscal-Q4 FY26 earnings ~2026-11-05 | falling · 18% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 12 | Taiwan monthly print ~2026-11-10 | rising · 94% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 27 | Taiwan monthly print ~2026-11-10 | quiet · 14% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 58 | — | falling · 68% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 89 | Taiwan monthly print ~2026-11-10 | falling · 2% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **quiet · 58%** (+2 pts vs last pulse, from 56%)
  - case: MediaTek Q3 +18% and Q4 NT$210-222B / 40-48% AI-ASIC guide are positive color on MEDIATEK but do not deliver the sealed September-2026 monthly YoY print; no TSM-MEDIATEK edge exists on the board to transmit TSM AI/CoWoS strain into that observable.
  - consensus: Street holds MEDIATEK strong_buy with 0q revenue growth ~0.46 and no TSM-MEDIATEK foundry wire on the board.
  - deviation: UNCHANGED — AI-ASIC ramp headlines reinforce MediaTek strength but leave the unwired-edge thesis and the specific monthly print untouched.
  - synthesis: Stand down; do not trade a TSM-MEDIATEK allocation story off Q3/Q4 guide until the sealed September monthly YoY actually posts.
  - confidence: Slight lift from Q3 +18% and Q4 AI guide making a Sept YoY <5% unlikely, offset by still-missing sealed monthly print and zero board edge.
  - evidence: `CBMiYkFVX3lxTE83cmx0TDB5dzlO`

- `jobA-20260727T075315Z-C4` — **falling · 1%** **⚠ FLAGGED**
  - case: HBM sold-out-to-2029 LTAs, Micron shortage-to-2030, and cluster-wide capacity adds travel MU__SKHYNIX__hbm_capacity as scarcity tailwinds with zero CXMT/commodity-DRAM margin evidence into the sealed MU GM <=55% test.
  - consensus: MU strong_buy, 0q rev growth ~3.5x as pure HBM-scarcity winner.
  - deviation: WEAKENING — window only reinforces HBM scarcity; commodity-DRAM/CXMT undershoot mechanism remains invisible.
  - synthesis: GM short is dead; do not fade MU on CXMT/commodity while sold-out HBM headlines dominate.
  - confidence: Prior 1 held: as_of passed with still no GM print and only bullish HBM cluster evidence.
  - evidence: `CBMilwFBVV95cUxQU0U1YVNiM2Nl`, `CBMiigFBVV95cUxOSWpYNG9OYkRW`, `CBMinwFBVV95cUxQejYtbllZVjZ0`
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `jobA-20260729T064012Z-C6` — **rising · 42%** (+24 pts vs last pulse, from 18%)
  - case: Amkor Q3 miss-estimates headline plus wall 0q growth now 3.56% show the AAPL__AMKR__osat_packaging consumer book capping near-term YoY even as $1.3-1.5B NVDA deal activates AMKR__TSM__adv_packaging_overflow for future capacity.
  - consensus: AMKR buy, framed as CoWoS-overflow AI packaging winner with ~20% growth previously cited.
  - deviation: STRENGTHENING — Q3 miss and sub-4% wall growth validate Apple-mix cap on this quarter's YoY despite NVDA packaging headlines.
  - synthesis: Lean <=15% YoY on the printed mix; treat NVDA $1.3B as forward capacity, not this-quarter overflow revenue.
  - confidence: Up from 18 on Q3 miss + wall growth collapsed to 3.56%; NVDA deal caps conviction because it can re-rate the next print.
  - evidence: `CBMi1wFBVV95cUxNajdaNnoyOGhV`, `CBMiuwFBVV95cUxORHNFUGxZMnZt`, `CBMirAFBVV95cUxNS3dfSXZNYi0y`, `CBMiygFBVV95cUxQSm83ZVRNV2pK`, `price_anomaly:AMKR:2026-11-0`

- `QCOM-septq-rev-yoy-2026` — **falling · 18%** (-10 pts vs last pulse, from 28%)
  - case: QCOM -11.1% (-4.4σ) price anomaly, weak profit outlook with faster Apple modem decline on AAPL__QCOM__handset_modems, Ultra flagship snubbing Snapdragon, and Exynos 2700 beating Snapdragon 8 Gen 6 on SAMSUNG__QCOM__handset_socs all push Sept-Q YoY toward or through the -12% fail line.
  - consensus: QCOM hold, 0q rev growth ~-10%, framed as Apple-insourcing structural decliner.
  - deviation: WEAKENING — handset/Apple cliff and Samsung Exynos snub dominate; AI HBC tape-out is 2027 and does not offset the sealed Sept-Q print.
  - synthesis: Cut conviction further on >-6.7% Sept-Q; print risk is now skewed to the fails_if side.
  - confidence: Down from 28 on -11% price shock, explicit faster-Apple-decline outlook, and Samsung flagship snub; HBC silicon is too late for this observable.
  - evidence: `price_anomaly:QCOM:2026-11-0`, `CBMiuwFBVV95cUxPUTN5ei10OERo`, `CBMitgFBVV95cUxOVGRrWmxlTzdN`, `CBMiywFBVV95cUxNZXEySWthRk54`, `CBMiyAFBVV95cUxNbHZqZmd1TDZN`

- `jobA-20260729T064012Z-C5` — **rising · 94%** (+2 pts vs last pulse, from 92%)
  - case: KLA Q3/Q1 sales top estimates, stock jump on beat, and AI/advanced-packaging deep-dive explicitly cite process-control pull via TSM__KLA__process_control, keeping Sept-Q YoY well above the 15% threshold.
  - consensus: KLA buy with weakest equipment-group rating/upside despite ~19% TSM concentration; 0q growth ~0.43 on wall.
  - deviation: STRENGTHENING — printed beat and AI/packaging commentary confirm the TSM-capex tailwind the rating still lags.
  - synthesis: Treat >=15% Sept-Q as confirmed; residual alpha is rating/multiple catch-up, not the revenue test.
  - confidence: Up from 92 on incremental beat headlines and TSM__KLA process-control callouts; only residual risk is classification of which fiscal quarter maps to the sealed key.
  - evidence: `CBMisAFBVV95cUxNcUNiLWs2MFcx`, `CBMipwFBVV95cUxPcm91dll6VlJm`, `CBMi5AFBVV95cUxQRldoSjdzbmo3`

- `jobA-20260726T115635Z-C4` — **quiet · 14%**
  - case: ASE LEAP target lift to $4B / 2027 doubling and Q3 +45% YoY confirm ASX AI-packaging fullness via ASX__TSM__adv_packaging_overflow, but nothing ties that demand into LRCX tool revenue or moves LRCX.rev_yoy toward 31%.
  - consensus: LRCX is strong_buy with ~62% 0q growth already baked; ASX is strong_buy on AI packaging.
  - deviation: UNCHANGED — ASX packaging strength is consensus-consistent and still unlinked to any LRCX-ASX equipment edge.
  - synthesis: Remain stood down on any LRCX-ASX edge trade; observable still unlinked to the claimed mechanism.
  - confidence: No LRCX print or ASX-capex-to-LRCX order path in window; prior 14 unchanged.
  - evidence: `CBMiYkFVX3lxTFBBTFNpMVhNM2ZS`, `CBMiqwFBVV95cUxOYV9iU1VHVG5M`, `CBMiqAFBVV95cUxNaWdIMWhXX3Iy`

- `HBM-zerosum-skhynix-spread-2026` — **falling · 68%** (-14 pts vs last pulse, from 82%)
  - case: SK Hynix Q3 profit >7x and $75B return plan plus shares spike raise SKHYNIX absolute return, while Altman/OpenAI 80% HBM lock and Samsung HBM4 sold-out-2027 run through SAMSUNG__NVDA__hbm and MU__SKHYNIX__hbm_capacity as co-rally, not SKHYNIX relative underperformance.
  - consensus: MU/SKHYNIX/SAMSUNG all strong_buy with triple-digit AI/HBM growth baked uniformly.
  - deviation: WEAKENING — SKHYNIX profit spike and cluster-wide sold-out-to-2029 LTAs reduce odds of a <=-10% SKHYNIX vs MU/SAMSUNG total-return spread.
  - synthesis: Dial back the SKHYNIX underperformance lean; window shows co-extension of HBM wallets, not zero-sum share shift against SKHYNIX.
  - confidence: Cut from 82 because SKHYNIX 7-fold profit/return spike directly lifts its total-return leg; Samsung share-gain color still present but no longer dominant.
  - evidence: `CBMilwFBVV95cUxQOTE5NTMtYklo`, `CBMidkFVX3lxTE4tcnZLYTBNcEFZ`, `CBMiigFBVV95cUxOSWpYNG9OYkRW`, `CBMikgFBVV95cUxOdjBtenp5UGRZ`, `CBMirgFBVV95cUxPN1Fva1BkZVk3`

- `AVGO-wafer-hike-multiple-2027` — **falling · 2%** **⚠ FLAGGED**
  - case: Baird $630 / Anthropic $63B deal upgrades and TSM CoWoS +20% price-hike headlines travel TSM__AVGO__foundry_wafers as demand/financing positives, not a 2027 wafer-cost multiple crush into AVGO <=480.
  - consensus: AVGO strong_buy, target ~527, price ~333; AI backlog/Anthropic narrative dominates.
  - deviation: WEAKENING — Anthropic capacity financing and analyst upgrades further bury the wafer-hike-as-margin-shock frame.
  - synthesis: Keep the Jan-2027 <=480 short stood down; live transmission is Anthropic/AI content, not wafer-cost multiple compression.
  - confidence: Prior 2 held: positive AVGO-specific deal flow and no wafer-hike print leave almost no path to a sub-480 close by Jan 2027 on cost-shock thesis.
  - evidence: `CBMinwFBVV95cUxNVWdPdllxMmRO`, `CBMinwFBVV95cUxPU3JPU3dqekJT`, `CBMihAFBVV95cUxNZG9jRG4zcDRi`, `CBMifkFVX3lxTE1Ma2pzMWkya2t5`
  - ⚠ **alert** (low_confidence): confidence 2% <= 10%

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
- AAPL dir `+` stress 16.2996
- TSM__AAPL__leading_edge_soc dir `+` stress 12.1186

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
