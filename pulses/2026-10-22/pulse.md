# ADF PULSE — 2026-10-22

- epoch: v1  ·  run (UTC): `2026-10-22T16:27:38Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 0 proposed  ·  0 resolved since last pulse  ·  8 assessed (3 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 9 | — | quiet · 56% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 9 | SK hynix Q3 earnings ~2026-10-24 | falling · 1% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 9 | — | falling · 1% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 24 | QCOM fiscal-Q4 FY26 earnings ~2026-11-05 | falling · 48% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 24 | Taiwan monthly print ~2026-11-10 | rising · 86% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 39 | Taiwan monthly print ~2026-11-10 | falling · 18% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 70 | SK hynix Q3 earnings ~2026-10-24 | rising · 74% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 101 | Taiwan monthly print ~2026-11-10 | quiet · 3% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **quiet · 56%**
  - case: No MediaTek September-2026 monthly revenue print appears; the MediaTek/Nvidia investment headline and TSM capacity items do not speak to MEDIATEK.revenue_growth YoY.
  - consensus: Street holds MediaTek 0q revenue growth at -0.0245 with a strong_buy framing on AI/handset recovery.
  - deviation: UNCHANGED — still no print to test the >=5% deviation from the -2.45% wall.
  - synthesis: Stand by for the Taiwan monthly print; do not act on Nvidia-investment or TSM-allocation headlines for this observable.
  - confidence: Unchanged from prior: no actual_key observation this window, so base rate on the sealed print date still governs.

- `jobA-20260727T075315Z-C4` — **falling · 1%** **⚠ FLAGGED**
  - case: Micron $54.23B quarter and $61.5B next-quarter guide plus Jensen ‘no 2029 glut’ and HBM4 sales +331% keep the HBM-scarcity winner frame intact — opposite of commodity-DRAM margin undershoot to <=55% GM.
  - consensus: MU strong_buy with 0q revenue growth ~3.5x and HBM scarcity fully priced.
  - deviation: WEAKENING — blockbuster print/guide and shortage-through-2028 chorus bury the CXMT-margin short.
  - synthesis: GM short is dead; do not fade MU on commodity-DRAM risk while HBM allocation headlines dominate.
  - confidence: Held at 1: another clean HBM-winner evidence set with zero CXMT/margin-pressure item.
  - evidence: `CBMie0FVX3lxTE4wOEdUcTdhQnNs`, `CBMihwFBVV95cUxPT2F6ekhMbjE1`, `CBMiV0FVX3lxTE1FbFp0TFdlVnpG`
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 1%** (-1 pts vs last pulse, from 2%) **⚠ FLAGGED**
  - case: Amkor $1.3B Nvidia Korea expansion plus $3B AI-packaging push across Korea/Arizona activate AMKR__TSM__adv_packaging_overflow at scale; Apple U.S. packaging expansion also adds, not caps — both push rev growth away from <=15%.
  - consensus: Wall still shows AMKR 0q growth only ~2.7% with a tame buy rating despite AI-packaging chatter.
  - deviation: WEAKENING hard — multi-source $1.3B/$3B NVDA capacity deals falsify the ‘Apple-mix caps AI upside’ short.
  - synthesis: Do not lean <=15%; overflow edge is live and trajectory already failed the short.
  - confidence: Held near floor (from 2→1): $1.3B NVDA deal cluster and Apple packaging expand both move observable the wrong way for the short.
  - evidence: `CBMivgFBVV95cUxOWGg0MEZTY19J`, `CBMiqgFBVV95cUxORndIcVN0eGtB`, `CBMirgFBVV95cUxObENLT195ZXdB`, `CBMirAFBVV95cUxNeFVHN0FRckxz`, `CBMi0gFBVV95cUxNUWNOOEI3bzRW`
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `QCOM-septq-rev-yoy-2026` — **falling · 48%** (-10 pts vs last pulse, from 58%)
  - case: Cluster of global layoff reports (phone-related jobs cut, performance-focused restructuring from November) with no offsetting Samsung flagship-SoC revenue disclosure — weakens the case that Sept-Q YoY clears -6.68%.
  - consensus: Street already frames QCOM as hold/structural decliner with 0q rev growth ~-10%.
  - deviation: WEAKENING — layoff wave reinforces the decliner frame and undercuts the Samsung-win offset the claim needs.
  - synthesis: Trim conviction on >-6.7% Sept-Q beat; handset-job cuts raise odds the print sits at or below wall.
  - confidence: Cut from 58 on multi-source global layoff cascade with zero positive SAMSUNG__QCOM__handset_socs revenue evidence.
  - evidence: `CBMizAFBVV95cUxPVW1scHA5VGEy`, `CBMiiwFBVV95cUxPbk9YWWg5Qkdh`, `CBMimgFBVV95cUxPWXVHU1U0LVJs`, `CBMi5gFBVV95cUxPdVZvQ1JvU2hW`

- `jobA-20260729T064012Z-C5` — **rising · 86%** (+2 pts vs last pulse, from 84%)
  - case: TSMC spending up to $64B and ‘chip stocks snap losing streak on TSMC spending’ explicitly tag TSM__KLA__process_control — capex tailwind into the sealed Sept-Q >=15% YoY observable; rare-earth motor-sourcing noise is secondary.
  - consensus: KLA is the laggard equipment name (buy not strong_buy, 0q growth ~0.26, lowest upside vs peers).
  - deviation: STRENGTHENING — TSM capex headlines re-assert the 0.19 concentration tailwind the claim says is under-priced.
  - synthesis: Hold the Sept-Q >=15% long as base case; TSM spend is the confirming mechanism.
  - confidence: Nudge from 84 on direct TSM-spend items wired to TSM__KLA__process_control; rare-earth equipment-alternative headlines keep a small haircut.
  - evidence: `CBMi_gFBVV95cUxPM3REUUdDSmtj`, `CBMioAFBVV95cUxNM0pEUUlLSGxj`, `CBMixwFBVV95cUxOVDZiLXZ3MjNB`

- `jobA-20260726T115635Z-C4` — **falling · 18%** (-10 pts vs last pulse, from 28%)
  - case: LRCX Q1 print is repeatedly cited as revenue up ~22% to $8.22B with supply-chain bottlenecks capping FQ2 sales — that YoY run-rate sits below the sealed >=31% confirm and even the <29% fail line; no LRCX→ASX equipment disclosure appears.
  - consensus: Wall prices LRCX as strong_buy with 0q revenue growth ~0.62 and AI-WFE supercycle intact.
  - deviation: WEAKENING — reported ~22% YoY plus explicit supply-bottleneck guidance move the observable away from the claim's beat-29% thesis.
  - synthesis: Observable is tracking toward fail; remain stood down on any LRCX-ASX edge trade until a direct packaging-tool disclosure.
  - confidence: Cut from 28 because the 22% YoY print and bottleneck guidance are direct negative reads on rev_yoy vs the 0.31 threshold.
  - evidence: `CBMinAFBVV95cUxOTjQ3a2dnTVg2`, `CBMivwFBVV95cUxQeUNVOGM3bXRp`, `CBMimAFBVV95cUxQaDhUV3k4ZFc1`, `CBMiXkFVX3lxTE10YVFhOWV1S09E`

- `HBM-zerosum-skhynix-spread-2026` — **rising · 74%** (+7 pts vs last pulse, from 67%)
  - case: Bernstein: Samsung overtook SK hynix in HBM revenue in 3Q26; Samsung 80% of 2027 memory output booked and taps TSMC for NVHBM base die — share shift travels MU__SKHYNIX__hbm_capacity and SAMSUNG__NVDA__hbm against SKHYNIX__NVDA__hbm, supporting SKH relative underperformance vs MU/SAMSUNG.
  - consensus: Street treats MU/SKHYNIX/SAMSUNG as a uniform HBM-scarcity rally (all strong_buy, multi-turn revenue growth).
  - deviation: STRENGTHENING — first hard HBM-revenue leadership flip plus Samsung booking share make the zero-sum edge live.
  - synthesis: Lean the <=-10% SKHYNIX-vs-MU/SAMSUNG spread; relative loser is now visible on board edges.
  - confidence: Raised from 67 on the Bernstein HBM-revenue overtake and Samsung 80% booking; still capped by Nomura/Jensen shortage-through-2028 tide that lifts all three.
  - evidence: `CBMiwwFBVV95cUxPRkdYb2VMZGRv`, `CBMijgFBVV95cUxPVGxYd3hVeEFu`, `CBMiV0FVX3lxTE9xakFrSW1FZmdx`, `CBMiigFBVV95cUxObV9hd203cWgw`, `CBMidkFVX3lxTE04RVFaOXEtekc3`

- `AVGO-wafer-hike-multiple-2027` — **quiet · 3%** **⚠ FLAGGED**
  - case: Window is pure TSM capacity/AI-allocation noise (HBM base-die at TSMC, Apple 1.4nm buyout, Moody’s Aa2); no 2027 wafer-price-hike confirmation and nothing that compresses AVGO multiple toward <=480.
  - consensus: AVGO strong_buy, target ~528, 0q rev growth ~0.94 — AI ASIC/custom silicon scarcity fully priced as positive.
  - deviation: UNCHANGED — cost-shock deviation still untested; path-of-least-resistance remains higher on allocation scarcity along TSM__AVGO__foundry_wafers.
  - synthesis: Keep the Jan-2027 <=480 short stood down; no hike-transmission evidence this window.
  - confidence: Flat at 3: still no wafer-price catalyst and TSM demand headlines keep the multiple-support bias intact.
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
