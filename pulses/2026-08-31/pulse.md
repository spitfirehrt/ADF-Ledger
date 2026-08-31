# ADF PULSE — 2026-08-31

- epoch: v1  ·  run (UTC): `2026-08-31T05:53:28Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **9 open sealed claim(s)** (8 ALPHA / 1 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 1 active / 1 proposed  ·  0 resolved since last pulse  ·  9 assessed (1 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260727T075315Z-C8` | CONSENSUS-HOLDS · graded (shadow-rate) | TSM · TSM__NVDA__leading_edge_wafers,TSM__AVGO__foundry_wafers,TSM__AMD__leading_edge_wafers | TSM September-2026 monthly revenue print, YoY  [>= +40%] | [1] | evidence-accumulating | 15 | Taiwan monthly print ~2026-09-10 | rising · 90% |
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 61 | Taiwan monthly print ~2026-09-10 | quiet · 26% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 61 | MU pre-announcement window ~2026-09-10 | falling · 8% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 61 | Taiwan monthly print ~2026-09-10 | falling · 35% |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 76 | Samsung Q3 preliminary guidance ~2026-10-08 | falling · 31% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 76 | Taiwan monthly print ~2026-09-10 | rising · 74% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 91 | Taiwan monthly print ~2026-09-10 | quiet · 30% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 122 | MU pre-announcement window ~2026-09-10 | falling · 11% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 153 | Taiwan monthly print ~2026-09-10 | rising · 34% |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260727T075315Z-C8` — **rising · 90%** (+2 pts vs last pulse, from 88%)
  - case: AI capacity fully booked + 10–15% wafer price hikes on TSM__NVDA/AMD/AVGO edges, 73% foundry share, and NVDA runway extension all support September monthly YoY still ≥40%.
  - consensus: TSM 0q growth ~+47% already baked; street agrees with the ≥40% path.
  - deviation: STRENGTHENING — booked capacity, price hikes, and share gap reinforce the calibration anchor.
  - synthesis: Base case remains September YoY ≥40%; hold as the book’s calibration anchor.
  - confidence: Booked-capacity and price-hike stack lifts prior 88; CoWoS bottleneck is the only modest offset.
  - evidence: `CBMidkFVX3lxTE9HWGt6N2ZueEJI`, `CBMikgFBVV95cUxNb3FzMVRoOUdY`

- `jobA-20260726T115635Z-C11` — **quiet · 26%**
  - case: Samsung Galaxy S27 MediaTek AP win is a 2027 handset design-win and does not move the September-2026 monthly YoY print; TSM capacity/price items stay on other foundry edges.
  - consensus: Street holds MediaTek 0q revenue growth near -2.45% with no wired TSM leading-edge edge.
  - deviation: UNCHANGED — S27 AP headline is timing-mismatched to the sealed Sept-2026 monthly observable.
  - synthesis: Do not act; treat the edge as unproven and wait for the October monthly print.
  - confidence: No new path into the Sept-2026 YoY print; prior 26 held flat.
  - evidence: `CBMidkFVX3lxTE14U0trYXdROGpJ`

- `jobA-20260727T075315Z-C4` — **falling · 8%** (-2 pts vs last pulse, from 10%) **⚠ FLAGGED**
  - case: MU/SKHYNIX/SAMSUNG 2027 sold-out, shortage-through-2030, and Micron capex double-to-$45B reinforce HBM/DRAM scarcity pricing; no CXMT commodity-share or ASP-down print to pull GM ≤55%.
  - consensus: MU pure HBM-scarcity winner with 0q growth ~+349% and strong_buy.
  - deviation: WEAKENING — sold-out and shortage-to-2030 evidence push margins the wrong way for the undershoot claim.
  - synthesis: Q4 GM ≤55% remains a low-probability tail; stand down until a commodity-DRAM ASP or CXMT-share print appears.
  - confidence: Scarcity cluster and capex double cut prior 10 further; zero commodity-pressure evidence.
  - evidence: `CBMiowFBVV95cUxPUkRBcDdpZmlu`
  - ⚠ **alert** (low_confidence): confidence 8% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 35%** (-7 pts vs last pulse, from 42%)
  - case: BofA Buy/$70 AI-packaging initiation and +9% gap-up plus TSMC CoWoS yield/cost bottlenecks (AMKR__TSM__adv_packaging_overflow) strengthen the overflow-principal framing the claim says is overstated vs Apple mix.
  - consensus: AMKR now re-rated as AI packaging beneficiary (BofA Buy, wall growth ~20%).
  - deviation: WEAKENING — AI-overflow initiation and CoWoS bottleneck headlines push expected growth away from the ≤15% cap.
  - synthesis: Apple-mix cap thesis is under pressure; wait for the next segment mix print before leaning into ≤15%.
  - confidence: BofA AI initiation and CoWoS bottleneck overflow cut prior 42; Apple book still the dominant sealed variable.
  - evidence: `CBMi0AFBVV95cUxOY21pc3pZWXBJ`, `CBMihAFBVV95cUxNS21BelZxQVg5`, `CBMidkFVX3lxTE01NFhwQ0RFYUtH`

- `QCOM-septq-rev-yoy-2026` — **falling · 31%** (-7 pts vs last pulse, from 38%)
  - case: Samsung-to-adopt-MediaTek-AP-for-Galaxy-S27 directly weakens SAMSUNG__QCOM__handset_socs, the sealed offset to Apple modem insourcing; Pixel-modem loss adds another handset share hit.
  - consensus: QCOM structural decliner (0q growth ~-10%, hold) via Apple modem insourcing.
  - deviation: WEAKENING — S27 MediaTek AP and Pixel modem losses cut the Samsung-offset case the claim needs.
  - synthesis: Stay sidelined into the print; Exynos/MediaTek headlines hurt the Samsung-offset case more than any HBC tease helps.
  - confidence: S27 MediaTek win pulls confidence down from prior 38; no offsetting Samsung SoC volume print.
  - evidence: `CBMidkFVX3lxTE14U0trYXdROGpJ`, `CBMijgFBVV95cUxOd0owRkVXRGlX`

- `jobA-20260729T064012Z-C5` — **rising · 74%** (+2 pts vs last pulse, from 72%)
  - case: TSMC additional $100B Arizona capex tags TSM__KLA__process_control; KLA advanced-node/HBM/packaging intensity pieces keep Sept-q ≥15% as base.
  - consensus: KLA weakest rating/upside in WFE group with 0q growth ~13–26% only.
  - deviation: STRENGTHENING — TSM Arizona $100B and process-control intensity headlines widen the under-priced gap.
  - synthesis: Sept-q ≥15% remains base case; the relative-rating gap is the alpha, not the growth print itself.
  - confidence: Arizona $100B and KLA node/HBM pieces nudge prior 72 up; insider selling is noise vs capex tailwind.
  - evidence: `CBMiV0FVX3lxTE5BeGJvVDU1Y3BG`, `CBMimgFBVV95cUxPZkNXa0FRT3l1`, `CBMimgFBVV95cUxQVGNIYldOTmJZ`

- `jobA-20260726T115635Z-C4` — **quiet · 30%**
  - case: LRCX Oregon lab/capex expansions and ASE record Q2 advanced-packaging revenue run in parallel on AI demand; no shipment or tool-of-record link that would wire an LRCX→ASX equipment edge.
  - consensus: LRCX 0q growth ~29% / strong_buy; ASX advanced-packaging momentum already in the wall.
  - deviation: UNCHANGED — dual AI-demand headlines do not create the missing supply edge.
  - synthesis: Observable stays at consensus until a shipment or design-win link appears; no action.
  - confidence: Still no LRCX-ASX mechanism in the window; confidence unchanged from prior 30.

- `HBM-zerosum-skhynix-spread-2026` — **falling · 11%** (-3 pts vs last pulse, from 14%)
  - case: 2027 memory sold-out across MU/SKHYNIX/SAMSUNG, CEO shortage-through-2030, and Samsung NVHBM key-partner status keep the cluster as a rising tide; MU__SKHYNIX__hbm_capacity zero-sum is not biting.
  - consensus: Uniform strong_buy / multi-bagger HBM scarcity across MU, SK hynix, Samsung.
  - deviation: WEAKENING — joint sold-out and shortage-to-2030 prints erase near-term share-shift evidence the spread needs.
  - synthesis: Do not fade SKHYNIX on the spread; scarcity remains a rising tide until an allocation or qualification share print appears.
  - confidence: Sold-out-2027 and shortage-to-2030 cluster further cut prior 14; no negative share print.
  - evidence: `CBMiowFBVV95cUxPUkRBcDdpZmlu`, `CBMipwFBVV95cUxOS1F4dV9yWnVM`, `CBMidkFVX3lxTFBLWHRvbGQxMVY0`

- `AVGO-wafer-hike-multiple-2027` — **rising · 34%** (+6 pts vs last pulse, from 28%)
  - case: TSMC across-the-board 10–15% price-hike report tags TSM__AVGO__foundry_wafers and re-opens the 2027 wafer cost-shock path into AVGO multiples; Hock Tan $100B AI guide still fights compression.
  - consensus: AVGO strong_buy / ~$526 target with AI revenue trajectory treated as strictly positive.
  - deviation: STRENGTHENING — explicit 10–15% wafer hike print supplies the sealed negative-sign cost mechanism the street ignores.
  - synthesis: Size a small short-multiple only while price stays sub-480; hike is live but AI bid can still invalidate by Jan-2027.
  - confidence: Hike telemetry lifts confidence from prior 28; AI $100B guide and sub-fail threshold keep it well below 50.
  - evidence: `CBMidkFVX3lxTE4tbVFELTZYcFNJ`, `CBMifkFVX3lxTFBkbll4UnBOS1M3`

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
- AAPL dir `+` stress 25.0425

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
