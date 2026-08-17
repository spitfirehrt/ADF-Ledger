# ADF PULSE — 2026-08-17

- epoch: v1  ·  run (UTC): `2026-08-17T04:27:09Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **9 open sealed claim(s)** (8 ALPHA / 1 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 0 proposed  ·  0 resolved since last pulse  ·  9 assessed (0 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260727T075315Z-C8` | CONSENSUS-HOLDS · graded (shadow-rate) | TSM · TSM__NVDA__leading_edge_wafers,TSM__AVGO__foundry_wafers,TSM__AMD__leading_edge_wafers | TSM September-2026 monthly revenue print, YoY  [>= +40%] | [1] | evidence-accumulating | 29 | Taiwan monthly print ~2026-09-10 | rising · 78% |
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 75 | Taiwan monthly print ~2026-09-10 | quiet · 26% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 75 | MU pre-announcement window ~2026-09-10 | falling · 20% |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 75 | Taiwan monthly print ~2026-09-10 | falling · 24% |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 90 | Samsung Q3 preliminary guidance ~2026-10-08 | rising · 50% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 90 | Taiwan monthly print ~2026-09-10 | rising · 62% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 105 | Taiwan monthly print ~2026-09-10 | quiet · 30% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 136 | MU pre-announcement window ~2026-09-10 | falling · 22% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 167 | Taiwan monthly print ~2026-09-10 | falling · 28% |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260727T075315Z-C8` — **rising · 78%** (+6 pts vs last pulse, from 72%)
  - case: TSMC 44.7% sales surge, NVDA Feynman locking TSMC A16, AVGO $10.8B AI / $56B 2026 guide on TSM__AVGO__foundry_wafers, and 98% CoWoS-L yield all sustain leading-edge crowding that underwrites September monthly YoY >=40%.
  - consensus: Street already bakes ~+47% TSM growth and strong_buy; claim is the calibration anchor agreeing with that.
  - deviation: STRENGTHENING — July run-rate plus A16/CoWoS and AVGO demand make sub-40% the tail, not the base.
  - synthesis: Base case remains September YoY >=40%; hold as the book’s calibration anchor.
  - confidence: Prior 72 raised on the explicit 44.7% surge print plus Feynman-A16 and AVGO backlog confirmation.
  - evidence: `CBMi1wFBVV95cUxOeTBSQnowUG9C`, `CBMinAFBVV95cUxNbWVUWVhwUENV`, `CBMiZkFVX3lxTE1aTHdPY2N3ODJB`, `CBMib0FVX3lxTFByamVFQW1sY0pD`, `CBMirgFBVV95cUxPUzlaNzl5RlBM`, `CBMijAFBVV95cUxOS0kxMDFESkw0`

- `jobA-20260726T115635Z-C11` — **quiet · 26%** (-2 pts vs last pulse, from 28%)
  - case: SemiAnalysis TPU shipment cut drove a 4% MediaTek share plunge, but nothing in-window speaks to the sealed September-2026 monthly YoY print or proves a TSM→MEDIATEK foundry edge.
  - consensus: Street holds MediaTek as strong_buy with near-term revenue growth around +10% and no explicit TSMC-edge pricing.
  - deviation: UNCHANGED — the claimed unwired edge and Sept print remain untested; the TPU cut is a separate demand shock.
  - synthesis: Do not act; treat the edge as unproven and wait for the October monthly print.
  - confidence: Prior 28 trimmed slightly on the negative TPU/MediaTek item; still no path to the sealed observable.
  - evidence: `CBMidkFVX3lxTE9QU2ExdE9VWGZa`

- `jobA-20260727T075315Z-C4` — **falling · 20%** (-5 pts vs last pulse, from 25%)
  - case: UBS ‘structural reset’ / HBM-squeeze note on MU, Samsung mobile-memory prices tripling, and SK hynix HBM4E plus $38B fabs all travel MU__SKHYNIX__hbm_capacity as scarcity that lifts consolidated gross margin, pushing away from <=55%.
  - consensus: Street frames MU as an HBM-scarcity winner with extreme near-term growth (~+349%) and strong_buy.
  - deviation: WEAKENING — every tagged item is scarcity/pricing-up, with zero CXMT or commodity-DRAM margin evidence.
  - synthesis: Q4 GM <=55% is the low-probability tail while HBM tightness dominates; need commodity-DRAM proof to revive.
  - confidence: Prior 25 cut further on UBS structural-reset language and triple memory prices; no counter-evidence on commodity book.
  - evidence: `CBMikgFBVV95cUxQd2dCbmFfSFVZ`, `CBMidkFVX3lxTFBYQWpENU9yblMt`, `CBMihwFBVV95cUxNOFVvTHZvYmtl`, `CBMi2AFBVV95cUxPMGRnU3FwQ1o4`

- `jobA-20260729T064012Z-C6` — **falling · 24%** (-6 pts vs last pulse, from 30%)
  - case: NVIDIA’s $1.5B capacity deal with Amkor and TSMC 98% CoWoS-L yield travel AMKR__TSM__adv_packaging_overflow as AI/overflow strength that overpowers the Apple-consumer-packaging cap, pushing quarterly YoY away from <=15%.
  - consensus: Street still carries modest AMKR near-term growth (~3% on wall) under a buy, while narrative increasingly prices AI packaging.
  - deviation: WEAKENING — NVDA capacity deal and CoWoS overflow evidence argue the AI book can clear the Apple mix cap this cycle.
  - synthesis: Claim’s <=15% observable is moving away; Apple seasonality alone may not cap the print if overflow ramps.
  - confidence: Prior 30 cut on the explicit NVIDIA $1.5B capacity deal and CoWoS-L yield item that validate the overflow leg.
  - evidence: `CBMiWEFVX3lxTE5JRVF2UkRJXzNr`, `CBMirgFBVV95cUxPUzlaNzl5RlBM`, `CBMi2AFBVV95cUxQSTNER2lKQ0pp`

- `QCOM-septq-rev-yoy-2026` — **rising · 50%** (+2 pts vs last pulse, from 48%)
  - case: Snapdragon C entry-laptop launch, Snapdragon 8 Elite Gen 6 Pro bench appearance, Stellantis Digital Chassis expansion, and a Q3 revenue beat collectively support Sept-q YoY clearing the -6.68% street frame; no fresh Samsung-SoC or Apple-modem print this window.
  - consensus: Street holds QCOM as hold with negative near-term rev growth (~-10% on the wall) framed around Apple modem risk.
  - deviation: STRENGTHENING modestly — PC/auto content offsets keep the path to >-6.68% open even without a new handset win headline.
  - synthesis: Directionally constructive into the Sept-q print; residual risk is handset ASP/unit softness, not the new laptop/auto book.
  - confidence: Prior 48 nudged up on revenue-beat and Snapdragon C/Stellantis items; wall growth still deeply negative so hurdle is low but not locked.
  - evidence: `CBMilwFBVV95cUxPdEFCT2ZsVklU`, `CBMi1gJBVV95cUxOWDQ3dkEzb29v`

- `jobA-20260729T064012Z-C5` — **rising · 62%** (+4 pts vs last pulse, from 58%)
  - case: KLA upgrades/strong-earnings/AI-outlook items plus AMAT record quarter and raised guide on TSM__AMAT__wfe_demand / SAMSUNG__AMAT__wfe_demand imply process-control follow-through on TSM__KLA__process_control into the Sept quarter >=15% YoY.
  - consensus: Street rates KLA only buy (weakest of WFE) with ~26% growth already on the wall, still below peers’ strong_buy framing.
  - deviation: STRENGTHENING — WFE AI demand and KLA-specific upgrades support clearing the 15% claim hurdle with room.
  - synthesis: TSM/Samsung capex tailwind is live; Sept-q >=15% is the base case despite softer relative rating.
  - confidence: Prior 58 raised on AMAT beat/raise as leading indicator for KLA process-control and on KLA upgrade notes; wall growth already >15%.
  - evidence: `CBMid0FVX3lxTFBkZTZoQnlZWS0y`, `CBMilAFBVV95cUxNX1AwVXpHMW1O`, `CBMipwFBVV95cUxNcV92WHpjbkh3`

- `jobA-20260726T115635Z-C4` — **quiet · 30%**
  - case: LRCX’s $3B global lab/R&D expansion and ASX’s AI-packaging Q2 print run in parallel; neither item creates or evidences an LRCX→ASX advanced-packaging equipment supply edge.
  - consensus: Street already prices LRCX at ~+53% rev growth / strong_buy and ASX at strong_buy on AI packaging.
  - deviation: UNCHANGED — lab capex and OSAT strength do not wire the missing supply edge or push LRCX YoY through the 31% claim threshold vs 29% consensus.
  - synthesis: Observable stays at consensus until a shipment or design-win link appears; no action.
  - confidence: Unchanged from prior: positive but non-linking prints leave the sealed edge and 31% hurdle untouched.
  - evidence: `CBMi_AFBVV95cUxOcGw1RjZ3Rmkw`, `CBMiogFBVV95cUxNRll2UDFEOHJV`

- `HBM-zerosum-skhynix-spread-2026` — **falling · 22%** (-6 pts vs last pulse, from 28%)
  - case: NVIDIA–SK hynix multiyear AI-memory partnership, HBM4E 12-layer samples, and $38B fab approvals all reinforce SKHYNIX__NVDA__hbm leadership; MU structural-reset and Samsung HBM-capacity unlocks lift the whole cluster, so SKHYNIX underperforming the MU/SAMSUNG mean by >=10% is less likely.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as uniform HBM-scarcity winners (all strong_buy, triple-digit growth).
  - deviation: WEAKENING — primary-supplier lock-in and dual expansion make the zero-sum underperformance leg harder to hit.
  - synthesis: Scarcity is still lifting all three; do not fade SKHYNIX on the spread until allocation share actually shifts.
  - confidence: Prior 28 cut on NVIDIA multiyear partnership and HBM4E samples that cement SKHYNIX primacy rather than relative lag.
  - evidence: `CBMiZEFVX3lxTE9uXzBzR3NhYkhm`, `CBMibEFVX3lxTE9hcUhKM0trcFhP`, `CBMihwFBVV95cUxNOFVvTHZvYmtl`, `CBMie0FVX3lxTE15Y1VubVVENUJI`, `CBMikgFBVV95cUxQd2dCbmFfSFVZ`

- `AVGO-wafer-hike-multiple-2027` — **falling · 28%** (-4 pts vs last pulse, from 32%)
  - case: AVGO AI chip revenue $10.8B / $30B+ backlog and $56B 2026 AI guide travel along TSM__AVGO__foundry_wafers as pure demand strength, lifting the multiple away from the <=480 confirm; financing-scare dips are second-order.
  - consensus: Street is strong_buy AVGO with mean target ~528 and ~85% near-term rev growth, treating AI demand as strictly positive.
  - deviation: WEAKENING — backlog/guide evidence reinforces the demand narrative and makes a hike-driven derating to <=480 less probable.
  - synthesis: Price path is still below 480 but momentum and backlog argue against confirmation; only explicit 2027 wafer-price commentary would reverse.
  - confidence: Prior 32 cut on $56B AI guide and $10.8B print; spot ~393 still under threshold but direction is wrong for the claim.
  - evidence: `CBMiZkFVX3lxTE1aTHdPY2N3ODJB`, `CBMib0FVX3lxTFByamVFQW1sY0pD`, `CBMivAFBVV95cUxQbEZoaVBBWWFS`, `CBMitgFBVV95cUxOQWxJWTBLRzhC`

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
