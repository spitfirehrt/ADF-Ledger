# ADF PULSE — 2026-10-08

- epoch: v1  ·  run (UTC): `2026-10-08T06:09:08Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 0 proposed  ·  0 resolved since last pulse  ·  8 assessed (3 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 23 | Taiwan monthly print ~2026-10-10 | quiet · 56% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 23 | SK hynix Q3 earnings ~2026-10-24 | falling · 1% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 23 | Taiwan monthly print ~2026-10-10 | falling · 2% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 38 | QCOM fiscal-Q4 FY26 earnings ~2026-11-05 | quiet · 70% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 38 | Taiwan monthly print ~2026-10-10 | rising · 88% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 53 | Taiwan monthly print ~2026-10-10 | quiet · 28% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 84 | SK hynix Q3 earnings ~2026-10-24 | rising · 55% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 115 | Taiwan monthly print ~2026-10-10 | falling · 3% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **quiet · 56%**
  - case: Window is pure TSMC Q3/September revenue prints (NT$1.49T, +50-54% YoY); zero MediaTek September-2026 monthly revenue telemetry, so the sealed MEDIATEK.revenue_growth observable is untouched.
  - consensus: Street holds MEDIATEK 0q revenue growth near -2.45% with strong_buy framing on handset recovery.
  - deviation: UNCHANGED — no MediaTek print arrived to test the >=5% YoY deviation.
  - synthesis: Stand by for the ~Oct 10 MediaTek Taiwan monthly; nothing in this window moves the claim.
  - confidence: Unchanged from prior: still pre-print, no new information on the observable.

- `jobA-20260727T075315Z-C4` — **falling · 1%** **⚠ FLAGGED**
  - case: Samsung/HBM boom cluster and JPMorgan $100B MU cash-windfall note reinforce HBM scarcity pricing; no CXMT commodity-DRAM margin evidence appears, and prior already marked the GM≤55% observable resolved against the claim.
  - consensus: Street frames MU as pure HBM-scarcity winner with 0q growth ~352% and strong_buy.
  - deviation: WEAKENING — window only adds AI-memory upside, nothing on commodity-DRAM undershoot.
  - synthesis: GM≤55% short fully retired; observable has resolved against the claim.
  - confidence: Floored at 1 per prior resolution; this window’s HBM-positive items cannot revive it.
  - evidence: `CBMimAFBVV95cUxOYXc4ZU1RNnlX`
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 2%** **⚠ FLAGGED**
  - case: AI-packaging/CoWoS-overflow narrative (Quiver) continues to dominate AMKR headlines ahead of Oct 26 print; no Apple consumer-packaging weakness item appears to pull revenue growth toward the <=15% cap.
  - consensus: Street still embeds elevated AMKR growth (cited ~19.8%) on AI packaging despite Apple OSAT weight.
  - deviation: WEAKENING — window reinforces the AI-overflow frame the claim says is overstated.
  - synthesis: Do not lean ≤15%; AI narrative and prior prints already sit above the fail threshold.
  - confidence: Held at prior floor: still no evidence the Apple book is capping the print below 15%.
  - evidence: `CBMivwFBVV95cUxQN0E1eDZGRnRL`
  - ⚠ **alert** (low_confidence): confidence 2% <= 10%

- `QCOM-septq-rev-yoy-2026` — **quiet · 70%** (-2 pts vs last pulse, from 72%)
  - case: Huawei multi-year 5G/AI patent deal and Arm trial headlines move licensing optics but supply no FYQ4 revenue actual or Samsung/Apple handset-SoC volume print that would shift septq_rev_yoy versus -6.68%.
  - consensus: Street holds QCOM as structural decliner (0q growth ~-10%, hold) on Apple modem risk.
  - deviation: UNCHANGED — licensing noise does not re-cut the sealed Sept-quarter revenue path.
  - synthesis: Hold the >-6.7% long into Nov FYQ4; still waiting on the actual print, not the patent headlines.
  - confidence: Prior 72 trimmed slightly: Huawei deal is net-payer mixed and Arm trial is a drag, with no revenue actual yet.
  - evidence: `CBMilgFBVV95cUxOSFBBU3BPNktY`, `CBMiuAFBVV95cUxPS1VVb0RTQ1Nh`

- `jobA-20260729T064012Z-C5` — **rising · 88%** (-2 pts vs last pulse, from 90%)
  - case: Morgan Stanley notes KLA supply constraints easing and leading-logic mix as tailwind, tagged to TSM__KLA__process_control; TSMC US-capex step-up reinforces the same edge toward Sept-q >=15% YoY.
  - consensus: Street has KLA as the weakest-rated equipment name (buy, 0q growth ~26%, target ~233) despite TSM concentration.
  - deviation: STRENGTHENING — explicit leading-logic/TSM mix tailwind and constraint relief support the under-priced N2/capex claim.
  - synthesis: Sept-q ≥15% remains base case with incremental TSM-capex support; hold the long.
  - confidence: Prior 90 nudged down on simultaneous MS target cut 253→227, but fundamental constraint-ease item still dominates.
  - evidence: `CBMi5gFBVV95cUxPUk9ZejRfRHEz`, `CBMilAFBVV95cUxOVXVaZVdyN3lk`

- `jobA-20260726T115635Z-C4` — **quiet · 28%**
  - case: ASX LEAP/CoWoS overflow and LRCX MS PT/shipment-growth notes run in parallel; no item discloses an LRCX tool sale into ASX advanced packaging, so the LRCX.rev_yoy >=31% path stays untested.
  - consensus: Street has LRCX 0q growth ~29% and strong_buy; ASX framed on AI packaging overflow.
  - deviation: UNCHANGED — no joint LRCX-ASX equipment disclosure or LRCX quarter print.
  - synthesis: Remain stood down until a direct LRCX-ASX tool disclosure; observable still untested.
  - confidence: Unchanged: still no mechanism evidence linking LRCX shipments to ASX, and no LRCX actual yet.

- `HBM-zerosum-skhynix-spread-2026` — **rising · 55%** (+7 pts vs last pulse, from 48%)
  - case: Samsung HBM4E Nvidia/hyperscaler qual (KED) plus record OP on AI memory and Lisa Su HBM4 ask travel SAMSUNG__NVDA__hbm and MU__SKHYNIX__hbm_capacity, raising peer share versus locked SK Hynix supply and supporting a negative SKHYNIX-vs-peers spread.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as uniform HBM rally with strong_buy and triple-digit growth.
  - deviation: STRENGTHENING — Samsung qual and profit surge make the zero-sum edge live against the uniform-rally wall.
  - synthesis: Lean the Dec SKHYNIX-vs-peers spread short; Samsung share grab is now the live mechanism.
  - confidence: Prior 48 raised on concrete Samsung HBM4E qualification and peer-outlook items that activate the negative capacity edge.
  - evidence: `CBMid0FVX3lxTE1nN0Nxck1YZW5o`, `CBMiqgFBVV95cUxNR2drdFk1d3hS`, `CBMiVEFVX3lxTFBlQVdacXdKUzVK`, `CBMidkFVX3lxTFBwMjlRSHM3MC1S`

- `AVGO-wafer-hike-multiple-2027` — **falling · 3%** (-1 pts vs last pulse, from 4%) **⚠ FLAGGED**
  - case: Anthropic $42-60B financing and custom-chip headlines (TIKR/FT/Yahoo) plus TSMC AI revenue beat travel TSM__AVGO__foundry_wafers as pure demand tailwind, pushing AVGO price away from the <=480 multiple-compression threshold.
  - consensus: Street strong_buy AVGO with mean target ~531 and 0q growth ~94%, treating AI custom silicon as strictly positive.
  - deviation: WEAKENING — wafer-cost shock narrative is drowned by incremental AI deal flow and TSMC volume beat.
  - synthesis: Keep ≤480 short-multiple stood down; path of least resistance still higher into Jan-2027.
  - confidence: Prior 4 cut on fresh AVGO financing/stock-jump items that move price farther from the short threshold.
  - evidence: `CBMiggFBVV95cUxPbDVKOWFrV0w5`, `CBMimwFBVV95cUxOSkthNVJPVlVx`, `CBMiigFBVV95cUxOc09fa29TTjdp`
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
