# ADF PULSE — 2026-08-27

- epoch: v1  ·  run (UTC): `2026-08-27T04:08:24Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **9 open sealed claim(s)** (8 ALPHA / 1 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 2 active / 2 proposed  ·  0 resolved since last pulse  ·  9 assessed (1 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260727T075315Z-C8` | CONSENSUS-HOLDS · graded (shadow-rate) | TSM · TSM__NVDA__leading_edge_wafers,TSM__AVGO__foundry_wafers,TSM__AMD__leading_edge_wafers | TSM September-2026 monthly revenue print, YoY  [>= +40%] | [1] | evidence-accumulating | 19 | Taiwan monthly print ~2026-09-10 | rising · 88% |
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 65 | Taiwan monthly print ~2026-09-10 | quiet · 26% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 65 | MU pre-announcement window ~2026-09-10 | falling · 10% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 65 | Taiwan monthly print ~2026-09-10 | rising · 42% |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 80 | Samsung Q3 preliminary guidance ~2026-10-08 | falling · 38% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 80 | Taiwan monthly print ~2026-09-10 | rising · 72% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 95 | Taiwan monthly print ~2026-09-10 | quiet · 30% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 126 | MU pre-announcement window ~2026-09-10 | falling · 14% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 157 | Taiwan monthly print ~2026-09-10 | falling · 28% |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260727T075315Z-C8` — **rising · 88%** (+3 pts vs last pulse, from 85%)
  - case: NVDA Q2 revenue double to ~$96B, 70% FY2028 growth forecast, and AWS +2M GPU order travel TSM__NVDA__leading_edge_wafers as sustained N3/N2 crowding into the September monthly YoY ≥40% print.
  - consensus: TSM strong_buy with ~47% 0q revenue growth already baked as AI foundry anchor.
  - deviation: STRENGTHENING — NVDA beat-and-raise plus multi-year GPU add directly gates TSM leading-edge wafers.
  - synthesis: Base case remains September YoY ≥40%; hold as the book’s calibration anchor.
  - confidence: Prior 85 lifted on NVDA $96B / 70% growth / AWS 2M GPU evidence tightening the TSM demand path.
  - evidence: `CBMiakFVX3lxTE1BWEhVNnVLZHo3`, `CBMi4wFBVV95cUxNZUNocGNzT2FJ`

- `jobA-20260726T115635Z-C11` — **quiet · 26%**
  - case: Window items cover Apple M6/M5 Ultra on TSM and AMD packaging spend with TSM; nothing tags MEDIATEK revenue or a TSM-MEDIATEK foundry link, so the September YoY print is unmoved.
  - consensus: Street holds MEDIATEK 0q revenue growth near -2.45% with no wired TSM leading-edge edge.
  - deviation: UNCHANGED — no MediaTek monthly-revenue or foundry-allocation evidence this window.
  - synthesis: Do not act; treat the edge as unproven and wait for the October monthly print.
  - confidence: Prior 26 held; no MEDIATEK-tagged item arrived to move the observable off the wall.

- `jobA-20260727T075315Z-C4` — **falling · 10%** (-3 pts vs last pulse, from 13%) **⚠ FLAGGED**
  - case: Micron CEO supply-not-catching-until-2028, customers putting up $22B, data-centers wanting 50% more than shippable, and $50B revenue guide all travel MU__NVDA__hbm / MU__SKHYNIX__hbm_capacity as HBM-scarcity margin support — opposite the commodity-DRAM/CXMT undershoot to GM ≤55%.
  - consensus: MU strong_buy with ~349% 0q revenue growth baked as pure HBM-scarcity winner.
  - deviation: WEAKENING — every MU item this window reinforces scarcity pricing power, not CXMT commodity pressure.
  - synthesis: Q4 GM ≤55% remains a low-probability tail; stand down until a commodity-DRAM ASP or CXMT-share print appears.
  - confidence: Prior 13 cut further; $22B prepay and 2028 crunch alarm make the ≤55% GM path less likely.
  - evidence: `CBMijgFBVV95cUxNOGFTRllod0Iy`, `CBMi7gFBVV95cUxPb0FtSGVyMzNE`, `CBMitAFBVV95cUxOVW44UW9zZ0wy`
  - ⚠ **alert** (low_confidence): confidence 10% <= 10%

- `jobA-20260729T064012Z-C6` — **rising · 42%** (+4 pts vs last pulse, from 38%)
  - case: AMKR -4.7% vs OSAT peers and softer near-term outlook headlines, with TSMC packaging-shift only latent on AMKR__TSM__adv_packaging_overflow, keep the Apple-mix cap on AI upside and the ≤15% YoY path in base case.
  - consensus: AMKR framed as CoWoS-overflow AI packaging with ~20% 0q growth baked.
  - deviation: STRENGTHENING — price divergence and soft-outlook items confirm consumer-packaging dominance over overflow upside.
  - synthesis: Miss-and-crash moves the ≤15% path into base case; lean into the claim on the next mix print rather than fade it.
  - confidence: Prior 38 raised on AMKR peer-relative selloff and soft-outlook items without a live overflow volume print.
  - evidence: `price_anomaly:AMKR:2026-08-2`, `CBMiqAFBVV95cUxQeFZVcDJqcHJG`, `CBMihgFBVV95cUxNLXhDWEMzc0ky`

- `QCOM-septq-rev-yoy-2026` — **falling · 38%** (-4 pts vs last pulse, from 42%)
  - case: Samsung Exynos 2700 outperforming the Snapdragon slated for Galaxy S27 Ultra hits SAMSUNG__QCOM__handset_socs; Xiaomi in-house Xring O3 challenges QCOM/MEDIATEK; 5GHz Oryon teases do not offset the SoC-win leg into the Sept-q YoY.
  - consensus: QCOM hold, 0q rev growth ~-10% framed as structural modem/SoC share loss.
  - deviation: WEAKENING — Exynos-outperform and OEM in-house chips cut the Samsung-offset case.
  - synthesis: Stay sidelined into the print; Exynos headlines hurt the Samsung-offset case more than S27 teases help.
  - confidence: Prior 42 cut on Exynos-vs-Snapdragon and Xiaomi Xring items without a confirming Samsung flagship SoC win.
  - evidence: `CBMiggFBVV95cUxOdEwxVkFJZzlG`, `CBMiwgFBVV95cUxQTDVfX3dPTTNC`, `CBMidkFVX3lxTE14aTRoQ05oMlJT`

- `jobA-20260729T064012Z-C5` — **rising · 72%** (+2 pts vs last pulse, from 70%)
  - case: KLA items on advanced-nodes/HBM/packaging gains and earnings beat/backlog, plus TSM strong Q2 tagged to TSM__KLA__process_control, support September-q YoY ≥15% on the N2/process-control tailwind.
  - consensus: KLA buy with ~13.5–26% 0q growth — lowest upside/rating in the equipment group.
  - deviation: STRENGTHENING — beat/backlog plus TSM process-control tag keep the ≥15% path intact; rating gap is the alpha.
  - synthesis: Sept-q ≥15% remains base case; the relative-rating gap is the alpha, not the growth print itself.
  - confidence: Prior 70 nudged up on KLA beat/backlog and TSM-tagged process-control items with no contrary miss.
  - evidence: `CBMihAFBVV95cUxQNzllaV9VbTFP`, `CBMi0wFBVV95cUxQalZHWS04SHpP`, `CBMiZkFVX3lxTFBCNnl2aGZVWHcy`

- `jobA-20260726T115635Z-C4` — **quiet · 30%**
  - case: LRCX Oregon R&D lab groundbreakings and an ASE facility-engineering contract sit on isolated nodes; no LRCX→ASX advanced-packaging equipment shipment or design-win appears.
  - consensus: LRCX 0q revenue growth ~52.8% / cited ~29% with ASX unwired to LRCX.
  - deviation: UNCHANGED — capex headlines do not create the missing supply edge or move LRCX YoY vs 31%.
  - synthesis: Observable stays at consensus until a shipment or design-win link appears; no action.
  - confidence: Prior 30 held; Oregon spend and ASE contract are not transmission on the claimed edge.

- `HBM-zerosum-skhynix-spread-2026` — **falling · 14%** (-2 pts vs last pulse, from 16%)
  - case: Micron CEO scarcity-to-2028 and $22B customer prepay plus NVDA 70% growth and HBM price +50% 2027 lift the whole HBM pool along SKHYNIX__NVDA__hbm / MU__NVDA__hbm / SAMSUNG__NVDA__hbm; MU__SKHYNIX__hbm_capacity zero-sum does not yet force SKHYNIX underperformance vs MU/SAMSUNG.
  - consensus: Memory cluster uniformly strong-buy with outsized targets (MU/SKHYNIX/SAMSUNG all scarcity winners).
  - deviation: WEAKENING — rising-tide scarcity and NVDA demand dominate; no allocation share print for the spread.
  - synthesis: Do not fade SKHYNIX on the spread; scarcity is still a rising tide until an allocation or qualification share print appears.
  - confidence: Prior 16 edged down; MU crunch alarm and NVDA HBM-tagged beat reinforce co-movement over zero-sum.
  - evidence: `CBMijgFBVV95cUxNOGFTRllod0Iy`, `CBMi7gFBVV95cUxPb0FtSGVyMzNE`, `CBMi3wFBVV95cUxPakp4UVJ2RHE2`, `CBMikAFBVV95cUxNT0xSZ1lFTzBt`

- `AVGO-wafer-hike-multiple-2027` — **falling · 28%** (-3 pts vs last pulse, from 31%)
  - case: NVDA blowout and Apple 2nm M6/M5 Ultra plus AMD $10B TSM packaging reinforce AI-demand bid on TSM wafers; no explicit 2027 wafer-price hike lands on TSM__AVGO__foundry_wafers, so AVGO multiple stays supported above the ≤480 path.
  - consensus: AVGO strong_buy, target ~526, price 355 with AI-demand strictly positive on foundry customers.
  - deviation: WEAKENING — demand-side evidence dominates; cost-shock leg still absent.
  - synthesis: Price under 480 but size down the short-multiple until an explicit 2027 wafer hike prints; AI bid fights the thesis.
  - confidence: Prior 31 trimmed; NVDA/Apple/AMD demand items raise the bar for margin-compression without a hike print.
  - evidence: `CBMiakFVX3lxTE1BWEhVNnVLZHo3`, `CBMiuAFBVV95cUxNaFNZWnlDMmx2`, `CBMifkFVX3lxTE9DbFpNdHZxX3ND`

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
- `SHK-AAPL` AAPL dir `+` (active)

**proposed shocks (await operator approval):**
- TSM__AAPL__leading_edge_soc dir `+` stress 29.9069
- AAPL dir `+` stress 29.7586

**propagation rows:**

| name | impact | lands | path |
|---|--:|:--:|---|
| AVGO | +0.2565 | 1 | TSM__AVGO__foundry_wafers |
| AMD | +0.2040 | 0 | TSM__AMD__leading_edge_wafers |
| NVDA | +0.2040 | 0 | TSM__NVDA__leading_edge_wafers |
| AMKR | +0.0805 | 1 | AAPL__AMKR__osat_packaging |
| ASML | +0.0612 | 2 | ASML__TSM__euv_systems |
| KLA | +0.0513 | 2 | TSM__KLA__process_control |
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
