# ADF PULSE — 2026-08-20

- epoch: v1  ·  run (UTC): `2026-08-20T06:28:50Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **9 open sealed claim(s)** (8 ALPHA / 1 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 0 proposed  ·  0 resolved since last pulse  ·  9 assessed (0 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260727T075315Z-C8` | CONSENSUS-HOLDS · graded (shadow-rate) | TSM · TSM__NVDA__leading_edge_wafers,TSM__AVGO__foundry_wafers,TSM__AMD__leading_edge_wafers | TSM September-2026 monthly revenue print, YoY  [>= +40%] | [1] | evidence-accumulating | 26 | Taiwan monthly print ~2026-09-10 | rising · 82% |
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 72 | Taiwan monthly print ~2026-09-10 | quiet · 26% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 72 | MU pre-announcement window ~2026-09-10 | falling · 17% |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 72 | Taiwan monthly print ~2026-09-10 | falling · 22% |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 87 | Samsung Q3 preliminary guidance ~2026-10-08 | quiet · 48% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 87 | Taiwan monthly print ~2026-09-10 | rising · 66% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 102 | Taiwan monthly print ~2026-09-10 | quiet · 30% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 133 | MU pre-announcement window ~2026-09-10 | falling · 20% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 164 | Taiwan monthly print ~2026-09-10 | rising · 34% |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260727T075315Z-C8` — **rising · 82%** (+4 pts vs last pulse, from 78%)
  - case: NVDA books TSMC 1.6 nm A16 for Feynman H2’28, pledges up to $105B / 4.25 GW OpenAI Ports-Pike capacity, and Huang doubles sales path to $1T through 2027 — all travel TSM__NVDA__leading_edge_wafers (and TSM__AVGO__foundry_wafers / TSM__AMD__leading_edge_wafers via the $597B cloud-capex winner framing) into September monthly revenue.
  - consensus: Street already bakes ~+46% TSM 0q growth and treats leading-edge AI demand as durable.
  - deviation: STRENGTHENING — multi-source NVDA/OpenAI capacity guarantees and next-node booking raise the odds September YoY clears the 40% calibration floor.
  - synthesis: Base case remains September YoY ≥40%; hold as the book’s calibration anchor.
  - confidence: Raised 4 pts on the $105B OpenAI backstop cluster plus explicit Feynman 1.6 nm booking; only a sudden monthly miss can break it.
  - evidence: `CBMisAFBVV95cUxPV1FObEhobkJp`, `CBMivAFBVV95cUxNODFyY0V6cUYt`, `CBMiwAFBVV95cUxOZkxQZ0FIUUQ0`, `CBMixwFBVV95cUxOc01TUnB1Y0po`, `CBMidkFVX3lxTFBVMDVfdXM4dHRi`

- `jobA-20260726T115635Z-C11` — **quiet · 26%**
  - case: All tagged items are TSM/NVDA leading-edge and Arizona capex; zero MediaTek revenue, design-win, or foundry-allocation prints. Nothing moved the September YoY observable.
  - consensus: Street holds MediaTek 0q revenue growth near -2.45% with a strong_buy rating and no wired TSM edge.
  - deviation: UNCHANGED — the hypothesized TSM→MEDIATEK edge remains untested by any MediaTek-specific evidence this window.
  - synthesis: Do not act; treat the edge as unproven and wait for the October monthly print.
  - confidence: Unchanged from prior: no MediaTek data arrived, so probability of a ≥5% Sept YoY print is still a low prior.

- `jobA-20260727T075315Z-C4` — **falling · 17%** (-3 pts vs last pulse, from 20%)
  - case: BofA FY2030 EPS >$236 / 34% CAGR, White House push of Apple off Chinese DRAM, Musk ‘memory bottleneck,’ and MU/SK capacity landing only post-2028 all tighten HBM/DRAM pricing via MU__NVDA__hbm and MU__SKHYNIX__hbm_capacity — opposite of a ≤55% GM path. Druckenmiller exit is the sole contrary tape.
  - consensus: Street frames MU as pure HBM-scarcity winner (strong_buy, +349% 0q growth) with no commodity-DRAM margin haircut.
  - deviation: WEAKENING — every high-salience item extends the scarcity/pricing upcycle and pushes Q4 GM further above the 55% fail line.
  - synthesis: Q4 GM ≤55% remains a low-probability tail; stand down until a commodity-DRAM ASP or CXMT-share print appears.
  - confidence: Cut 3 pts: BofA long-duration EPS call, policy tailwind into Apple, and 2028 capacity lag all raise the odds GM clears 60%.
  - evidence: `CBMikAFBVV95cUxNcXBIUlMzQTBw`, `CBMilgFBVV95cUxOUUNqdHNyaTJi`, `CBMi2gFBVV95cUxOZ2s4Qy1ZSlJU`

- `jobA-20260729T064012Z-C6` — **falling · 22%** (-2 pts vs last pulse, from 24%)
  - case: AMKR advanced-packaging pipeline update and dividend-driven +6.7% tape reinforce the CoWoS-overflow AI narrative along AMKR__TSM__adv_packaging_overflow, working against the claim that the 29.8% AAPL__AMKR__osat_packaging book caps YoY ≤15%.
  - consensus: Street still carries AMKR 0q growth at only +2.9% (down sharply from the sealed 19.8% cite) with no rating — mixed on whether AI packaging or Apple mix dominates.
  - deviation: WEAKENING on mechanism (packaging-pipeline headlines fight the Apple-cap story) even as the lower wall estimate would mathematically favor ≤15% if it sticks.
  - synthesis: Claim’s ≤15% observable is not being helped by this window’s packaging bullishness; wait for the actual quarter mix print before acting.
  - confidence: Cut 2 pts: advanced-packaging pipeline update is direct counter-evidence to the Apple-cap mechanism even though wall growth collapsed.
  - evidence: `CBMilAFBVV95cUxOV1hkbjMwMFg0`

- `QCOM-septq-rev-yoy-2026` — **quiet · 48%** (-2 pts vs last pulse, from 50%)
  - case: Snapdragon X2 Elite laptop bench wins, a Snapdragon-X Googlebook tablet leak, and AIREV Dragonwing AI partnerships are PC/edge positives but do not touch SAMSUNG__QCOM__handset_socs or AAPL__QCOM__handset_modems volumes for the Sept-q print.
  - consensus: Street holds QCOM as a structural decliner (0q growth now -9.98%, hold) on Apple modem insourcing.
  - deviation: UNCHANGED — laptop/AI side-book noise does not move the sealed handset-offset thesis or the >-6.68% Sept-q hurdle.
  - synthesis: Stay sidelined into the print; need Samsung flagship SoC or modem-mix evidence, not PC design wins.
  - confidence: Trimmed 2 pts from prior: wall 0q growth worsened to -9.98% and this window added no handset-offset proof.
  - evidence: `CBMiqAFBVV95cUxQcEpZc2lIUlBK`

- `jobA-20260729T064012Z-C5` — **rising · 66%** (+4 pts vs last pulse, from 62%)
  - case: TSMC’s additional $100B Arizona commitment tags directly onto TSM__KLA__process_control, extending the N2/leading-edge process-control spend that underwrites KLA Sept-q YoY ≥15%.
  - consensus: Street rates KLA only buy with the weakest relative upside in WFE despite ~19% TSM concentration; 0q growth now printed at +25.9% on the wall.
  - deviation: STRENGTHENING — incremental TSM Arizona dollars are pure process-control fuel and pull the sealed ≥15% print further into base case.
  - synthesis: Sept-q ≥15% remains base case; the relative-rating gap is the alpha, not the growth print itself.
  - confidence: Raised 4 pts on the explicit $100B Arizona item wired to TSM__KLA__process_control; wall 0q already >15% reduces miss risk.
  - evidence: `CBMioAFBVV95cUxOS0hJanZXRVhi`

- `jobA-20260726T115635Z-C4` — **quiet · 30%**
  - case: ASX raised 2026 capex by $2B and posted a 27% revenue jump on AI/data-center demand, but no item names LRCX tools, shipments, or a design-win into ASE lines.
  - consensus: Street has LRCX at +52.8% 0q growth / strong_buy and ASX at +38% growth with no rating; no LRCX→ASX equipment edge is priced.
  - deviation: UNCHANGED — ASX demand strength is real but does not establish the sealed LRCX supply link needed to move LRCX rev YoY above 31%.
  - synthesis: Observable stays at consensus until a shipment or design-win link appears; no action.
  - confidence: Unchanged: ASX capex/revenue strength is necessary but not sufficient without an LRCX equipment tie.
  - evidence: `CBMilwFBVV95cUxOaVcxT0xRelIz`, `CBMikgFBVV95cUxOdVRZU3djTG9a`

- `HBM-zerosum-skhynix-spread-2026` — **falling · 20%** (-2 pts vs last pulse, from 22%)
  - case: NVDA’s $105B OpenAI/Ports-Pike guarantee and Huang’s $600B/$1T compute framing lift SKHYNIX__NVDA__hbm, MU__NVDA__hbm and SAMSUNG__NVDA__hbm together; Musk bottleneck and dual MU/SK capacity commits reinforce common scarcity, not share shift.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as uniform HBM rally (all strong_buy, triple-digit growth), ignoring zero-sum allocation.
  - deviation: WEAKENING — incremental NVDA demand and shared bottleneck commentary keep the cluster co-moving, pushing the SKHYNIX underperformance spread further from ≤-10%.
  - synthesis: Do not fade SKHYNIX on the spread; scarcity is still a rising tide until an allocation or qualification share print appears.
  - confidence: Cut 2 pts from prior: OpenAI/NVDA demand pulse and dual-supplier capacity headlines further delay any zero-sum realization before year-end.
  - evidence: `CBMixwFBVV95cUxOc01TUnB1Y0po`, `CBMimAFBVV95cUxOWkhlM2xEdzRv`

- `AVGO-wafer-hike-multiple-2027` — **rising · 34%** (+6 pts vs last pulse, from 28%)
  - case: BofA $370B AI-debt flag and 6% AVGO selloff plus Druckenmiller exiting AVGO compress the multiple along TSM__AVGO__foundry_wafers cost-pass-through risk; $30B AI orders do not offset the financing overhang into the ≤480 path.
  - consensus: Street is strong_buy AVGO with mean target ~528 and +84.5% 0q growth, treating AI backlog as strictly multiple-supportive.
  - deviation: STRENGTHENING — debt-financing and smart-money exit evidence reintroduce margin/multiple compression the AI-demand narrative ignores.
  - synthesis: Price already sits well below 480; keep the short-multiple thesis live but size small until explicit 2027 wafer-price commentary lands.
  - confidence: Raised from 28 on the BofA debt selloff and Druckenmiller exit; still capped because $30B AI orders and XPU narrative can re-expand the multiple before Jan-2027.
  - evidence: `CBMilwFBVV95cUxOZGJ3YTFSWEtr`, `CBMilwFBVV95cUxPelVLalFua0lu`, `CBMidkFVX3lxTE5nSEc3MHJTTVlf`

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
