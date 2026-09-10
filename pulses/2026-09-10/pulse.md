# ADF PULSE — 2026-09-10

- epoch: v1  ·  run (UTC): `2026-09-10T08:16:32Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **9 open sealed claim(s)** (8 ALPHA / 1 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 3 active / 3 proposed  ·  0 resolved since last pulse  ·  9 assessed (1 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260727T075315Z-C8` | CONSENSUS-HOLDS · graded (shadow-rate) | TSM · TSM__NVDA__leading_edge_wafers,TSM__AVGO__foundry_wafers,TSM__AMD__leading_edge_wafers | TSM September-2026 monthly revenue print, YoY  [>= +40%] | [1] | evidence-accumulating | 5 | — | rising · 95% |
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 51 | Taiwan monthly print ~2026-10-10 | quiet · 35% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 51 | MU fiscal-Q4 FY26 earnings ~2026-09-24 | falling · 4% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 51 | Taiwan monthly print ~2026-10-10 | falling · 14% |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 66 | Samsung Q3 preliminary guidance ~2026-10-08 | rising · 56% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 66 | Taiwan monthly print ~2026-10-10 | rising · 84% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 81 | Taiwan monthly print ~2026-10-10 | quiet · 29% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 112 | MU fiscal-Q4 FY26 earnings ~2026-09-24 | falling · 30% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 143 | Taiwan monthly print ~2026-10-10 | falling · 14% |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260727T075315Z-C8` — **rising · 95%** (+2 pts vs last pulse, from 93%)
  - case: TSMC August revenue +53% YoY record with AI demand outstripping supply on TSM__NVDA__leading_edge_wafers / TSM__AMD__leading_edge_wafers / TSM__AVGO__foundry_wafers makes September YoY ≥40% the clear base case.
  - consensus: TSM strong-buy, 0q growth ~46–47%, AI foundry scarcity fully priced.
  - deviation: STRENGTHENING — August +53% print and capacity-booked language raise odds the sealed ≥40% Sept print holds.
  - synthesis: Hold as the book’s calibration anchor; September YoY ≥40% remains base case.
  - confidence: Prior 93; confirmed August +53% across Bloomberg/CNBC/ANI adds 2 pts with almost no path under 40%.
  - evidence: `CBMiqwFBVV95cUxPYl9WbFZJWVZK`, `CBMipAFBVV95cUxQSlNRXzI3MFJ6`, `CBMipwFBVV95cUxNc3NHcjUtZ0Rj`, `CBMickFVX3lxTE9ycjd0eDNoeHBM`

- `jobA-20260726T115635Z-C11` — **quiet · 35%** (-1 pts vs last pulse, from 36%)
  - case: Window is pure TSM August +53% and Apple A20 2nm; zero MediaTek-tagged prints or design-win items, so the Sept MEDIATEK.revenue_growth observable is unmoved.
  - consensus: MEDIATEK wall holds mild contraction (0q growth ~-2.45%) and is unwired to TSM on the board.
  - deviation: UNCHANGED — no MediaTek-specific evidence this window to strengthen or weaken the missing-edge thesis.
  - synthesis: No action; wait for the Oct MediaTek monthly print; TSM strength alone does not move the sealed observable.
  - confidence: Prior 36 held; no MediaTek item appeared, so only a 1-pt drift for elapsed time with no new support.

- `jobA-20260727T075315Z-C4` — **falling · 4%** **⚠ FLAGGED**
  - case: Memory inventories crashing below 10 days industry-wide plus MU doubling HBM to ~100k wpm on MU__SKHYNIX__hbm_capacity push consolidated GM up, not toward the ≤55% short.
  - consensus: MU strong-buy with ~349% 0q rev growth priced as pure HBM-scarcity winner.
  - deviation: WEAKENING — shortage and HBM capacity expansion make GM≥60% the path of least resistance.
  - synthesis: Stand down the GM≤55% short; Q4 print is far more likely to clear 60%.
  - confidence: Prior 4 unchanged; another week of <10-day inventories and MU HBM double leaves no path to the short threshold.
  - evidence: `CBMizgFBVV95cUxQSTc2dzB4bHg1`, `CBMimgFBVV95cUxQcnB5dFEzMGc0`, `CBMiqAFBVV95cUxNcF83Mk13blR4`
  - ⚠ **alert** (low_confidence): confidence 4% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 14%** (-6 pts vs last pulse, from 20%)
  - case: Amkor $12B Peoria Phase-2 fill-capacity expansion explicitly tags AMKR__TSM__adv_packaging_overflow and AAPL__AMKR__osat_packaging, while Apple iPhone Duo/18 Pro launches add seasonal volume — both bias quarterly YoY above the ≤15% cap.
  - consensus: AMKR buy, 0q growth only ~2.7–20%, still debated as CoWoS-overflow vs Apple-packaging mix.
  - deviation: WEAKENING — $12B demand-filled expansion and iPhone cycle make ≥19.8% fail-band more likely than the ≤15% confirm.
  - synthesis: Do not lean into ≤15%; overflow edge is active and Apple launches bias the print higher.
  - confidence: Prior 20; $12B Arizona double and iPhone Duo/18 launches cut 6 pts against the low-growth confirm.
  - evidence: `CBMimwFBVV95cUxPU3cyTlBfUHhH`, `https://www.apple.com/newsro`, `CBMinAFBVV95cUxNV01oMnBsVVFU`

- `QCOM-septq-rev-yoy-2026` — **rising · 56%** (+8 pts vs last pulse, from 48%)
  - case: Amazon multi-gen custom AI inference/$60B chip pact is a new positive revenue vector that more than offsets the iPhone 18 Pro/Duo C2 modem ditch on AAPL__QCOM__handset_modems, biasing SeptQ YoY above the -6.68% hurdle.
  - consensus: QCOM hold, 0q rev growth ~-10%, framed as Apple-modem structural decliner.
  - deviation: STRENGTHENING — $60B AWS AI silicon deal is a concrete offset the street growth print has not yet absorbed.
  - synthesis: Lean long QCOM into the Nov FYQ4 print; Amazon AI content plus any residual Samsung SoC makes clearing -6.68% the base case.
  - confidence: Prior 48; Amazon $60B multi-gen deal adds ~10 pts, partially clawed back by the confirmed iPhone 18 modem loss (-2 net).
  - evidence: `CBMixAFBVV95cUxQTG12ci1fSmJS`, `CBMi3AFBVV95cUxPVm1nVlZ0Q2VB`, `CBMimAFBVV95cUxPa1dVV0FkV0JY`, `https://www.apple.com/newsro`

- `jobA-20260729T064012Z-C5` — **rising · 84%** (+2 pts vs last pulse, from 82%)
  - case: KLA Q4 AI-driven revenue jump (+7.3% stock) plus TSMC High-NA/large-mask commits travel TSM__KLA__process_control, supporting SeptQ YoY ≥15%.
  - consensus: KLA buy (weakest equipment rating), 0q growth ~13–26%, lagging AMAT/LRCX/ASML upside.
  - deviation: STRENGTHENING — AI revenue-jump print and TSM leading-edge capex tailwind keep the ≥15% print as base case.
  - synthesis: Sept-q ≥15% is base case; alpha remains the relative-rating gap vs AMAT/LRCX/ASML, not the print itself.
  - confidence: Prior 82; KLA AI revenue-jump item and continued TSM EUV commits add 2 pts.
  - evidence: `CBMi0AFBVV95cUxNRnRrTHltMmxH`, `CBMiTkFVX3lxTE9nSmxRNFVNTTQ1`, `CBMiqwFBVV95cUxPYl9WbFZJWVZK`

- `jobA-20260726T115635Z-C4` — **quiet · 29%** (-1 pts vs last pulse, from 30%)
  - case: ASE August revenue +34–46% and Lam ‘30% revenue jump’/earnings beat run in parallel; no item names an LRCX tool or process flowing into ASX advanced packaging, so the edge stays unproven.
  - consensus: LRCX wall already prices ~29–53% growth; ASX is strong-buy on AI packaging overflow from TSM.
  - deviation: UNCHANGED — coincident strength at both nodes without a named LRCX→ASX supply mechanism.
  - synthesis: No action; edge remains unproven until a direct LRCX-ASX tool or process link appears.
  - confidence: Prior 30; Lam’s reported ~30% jump sits on the 29–31 boundary and adds no edge proof, so confidence inches down 1 pt.
  - evidence: `CBMitwFBVV95cUxNeEVzVzNILThi`, `CBMirAFBVV95cUxNTFdrQUVpUGZV`

- `HBM-zerosum-skhynix-spread-2026` — **falling · 30%** (-8 pts vs last pulse, from 38%)
  - case: Samsung/SK hynix inventories <10 days and MU plan to double HBM to ~100k wpm hit MU__SKHYNIX__hbm_capacity / SKHYNIX__NVDA__hbm / SAMSUNG__NVDA__hbm as a uniform shortage rally, not a zero-sum share fight that forces SKH relative underperformance.
  - consensus: Memory cluster priced as uniform melt-up (MU/SKH/SAMSUNG all strong-buy, triple-digit growth).
  - deviation: WEAKENING — shared <10-day inventory crash and MU HBM doubling reinforce co-movement over the sealed negative spread.
  - synthesis: Reduce the relative underweight SKHYNIX; evidence this window favors continued cluster co-rally into the Dec spread print.
  - confidence: Prior 38; uniform inventory crash plus MU capacity double cut 8 pts because they argue against SKH-specific disappointment.
  - evidence: `CBMizgFBVV95cUxQSTc2dzB4bHg1`, `CBMiqAFBVV95cUxNcF83Mk13blR4`, `CBMimgFBVV95cUxQcnB5dFEzMGc0`, `CBMidkFVX3lxTE91NWdzVklPS0NE`

- `AVGO-wafer-hike-multiple-2027` — **falling · 14%** (-4 pts vs last pulse, from 18%)
  - case: Broadcom Q3 call $40B AI roadmap through 2028 plus $230B AI-semi 2028/$900-share narrative travel TSM__AVGO__foundry_wafers as pure demand, overpowering any 2027 wafer-cost shock toward the ≤480 multiple.
  - consensus: AVGO strong-buy, target ~533, 0q rev growth ~94%; street treats TSM supply as strictly positive for AVGO AI.
  - deviation: WEAKENING — AI-roadmap prints bias price path higher, away from the ≤480 confirmation band.
  - synthesis: Stand down the ≤480 short-multiple; path of least resistance remains higher into 2027.
  - confidence: Prior 18; $40B/2028 roadmap and $230B-2028 forecast cut another 4 pts as they push AVGO away from the short threshold.
  - evidence: `CBMiXkFVX3lxTE5yOVdlVTBnLUEx`, `CBMiqAJBVV95cUxNNWhxbVdMSHZh`, `CBMipwFBVV95cUxNc3NHcjUtZ0Rj`

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
- `SHK-TSM__AAPL__leading_edge_soc` TSM__AAPL__leading_edge_soc dir `+` (active)
- `SHK-AVGO__AAPL__wireless_content` AVGO__AAPL__wireless_content dir `+` (active)

**proposed shocks (await operator approval):**
- AAPL dir `+` stress 24.2468
- TSM__AAPL__leading_edge_soc dir `+` stress 21.2803
- AVGO__AAPL__wireless_content dir `+` stress 1.3402

**propagation rows:**

| name | impact | lands | path |
|---|--:|:--:|---|
| AMKR | +0.0805 | 1 | AAPL__AMKR__osat_packaging |
| TSM | +0.0408 | 0 | TSM__AAPL__leading_edge_soc |
| AVGO | +0.0360 | 1 | AVGO__AAPL__wireless_content |
| QCOM | +0.0255 | 1 | AAPL__QCOM__handset_modems |
| AVGO | +0.0174 | 1 | TSM__AAPL__leading_edge_soc → TSM__AVGO__foundry_wafers |
| AMD | +0.0139 | 0 | TSM__AAPL__leading_edge_soc → TSM__AMD__leading_edge_wafers |
| AVGO | +0.2565 | 1 | TSM__AVGO__foundry_wafers |
| AMD | +0.2040 | 0 | TSM__AMD__leading_edge_wafers |
| NVDA | +0.2040 | 0 | TSM__NVDA__leading_edge_wafers |
| AMKR | +0.0805 | 1 | AAPL__AMKR__osat_packaging |
| ASML | +0.0612 | 2 | ASML__TSM__euv_systems |
| KLA | +0.0513 | 2 | TSM__KLA__process_control |
| AMKR | +0.1207 | 1 | AAPL__AMKR__osat_packaging |
| TSM | +0.0612 | 0 | TSM__AAPL__leading_edge_soc |
| QCOM | +0.0382 | 1 | AAPL__QCOM__handset_modems |
| TSM | +0.0243 | 1 | TSM__AVGO__foundry_wafers |
| AMD | +0.0208 | 0 | TSM__AAPL__leading_edge_soc → TSM__AMD__leading_edge_wafers |
| NVDA | +0.0208 | 0 | TSM__AAPL__leading_edge_soc → TSM__NVDA__leading_edge_wafers |

## §5 — RESOLUTIONS (since last pulse)

_no resolutions since the last pulse._

## §6 — CHECKPOINT OUTCOMES (since last pulse)

_Raw comparisons against the frozen reference. A comparison, **not a grade** — claims are graded only at resolution._

_no checkpoint passed since the last pulse._

---
_Tiers are stated: §1 is graded; §2/§3 are ungraded. Internal machinery (checkup evidence, amendment queue, stress-ledger internals, judge/repair rationales) never ships. Map changes reach buyers as epoch-boundary changelogs._
