# ADF PULSE — 2026-09-14

- epoch: v1  ·  run (UTC): `2026-09-14T06:53:45Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **9 open sealed claim(s)** (8 ALPHA / 1 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 7 active / 7 proposed  ·  0 resolved since last pulse  ·  9 assessed (2 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260727T075315Z-C8` | CONSENSUS-HOLDS · graded (shadow-rate) | TSM · TSM__NVDA__leading_edge_wafers,TSM__AVGO__foundry_wafers,TSM__AMD__leading_edge_wafers | TSM September-2026 monthly revenue print, YoY  [>= +40%] | [1] | evidence-accumulating | 1 | — | rising · 97% |
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 47 | Taiwan monthly print ~2026-10-10 | quiet · 35% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 47 | MU fiscal-Q4 FY26 earnings ~2026-09-24 | falling · 5% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 47 | Taiwan monthly print ~2026-10-10 | falling · 10% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 62 | Samsung Q3 preliminary guidance ~2026-10-08 | rising · 63% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 62 | Taiwan monthly print ~2026-10-10 | rising · 85% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 77 | Taiwan monthly print ~2026-10-10 | quiet · 29% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 108 | MU fiscal-Q4 FY26 earnings ~2026-09-24 | rising · 38% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 139 | Taiwan monthly print ~2026-10-10 | falling · 12% |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260727T075315Z-C8` — **rising · 97%** (+2 pts vs last pulse, from 95%)
  - case: Multiple August prints at +53% YoY and a September-revenue-surges-53% headline, plus Huang supply-not-demand and AVGO/AMD/NVDA wafer pull on TSM__NVDA__leading_edge_wafers / TSM__AMD__leading_edge_wafers / TSM__AVGO__foundry_wafers, keep September YoY well above the 40% threshold.
  - consensus: TSM wall already bakes ~+46-47% 0q growth and strong_buy — claim is the calibration anchor agreeing with that.
  - deviation: STRENGTHENING — 53% August run-rate and September 53% headline leave almost no path under 40%.
  - synthesis: Hold as the book’s calibration anchor; September YoY ≥40% is now near-certain.
  - confidence: Up from 95: explicit September +53% headline plus sustained August 53% AI-demand cluster remove residual miss risk before as_of.
  - evidence: `CBMiTkFVX3lxTE1aTzR4TnFXdW1k`, `CBMidkFVX3lxTE5YNFhGZGUyVHZk`, `CBMilgFBVV95cUxQTnJIdnBOTlJT`

- `jobA-20260726T115635Z-C11` — **quiet · 35%**
  - case: Taipei Times notes MediaTek August record revenue alongside TSMC, but the sealed observable is the September-2026 MediaTek monthly YoY print (~Oct 10); nothing in-window moves that print.
  - consensus: MEDIATEK wall shows modest +10% 0q growth and strong_buy; cited_wall still anchors the fail side at -2.45%.
  - deviation: UNCHANGED — August co-print is not the sealed September observable.
  - synthesis: No action; wait for the Oct MediaTek September monthly print.
  - confidence: Unchanged from prior: TSM strength and one August MediaTek headline do not substitute for the sealed September print.

- `jobA-20260727T075315Z-C4` — **falling · 5%** (+1 pts vs last pulse, from 4%) **⚠ FLAGGED**
  - case: HBM4 shortage and DRAM inventory below 10 days plus 'HBM shortage strengthens Micron' travel MU__NVDA__hbm / MU__SKHYNIX__hbm_capacity toward fatter not thinner GM; DeepSeek KV-cache cut is the only soft offset and does not restore a ≤55% path.
  - consensus: MU wall is strong_buy with +348% 0q rev growth fully pricing an HBM-scarcity margin super-cycle.
  - deviation: WEAKENING — shortage/inventory evidence reinforces the high-GM consensus the claim bets against.
  - synthesis: Stand down the GM≤55% short; Q4 print is far more likely to clear 60%.
  - confidence: Up 1pt only on DeepSeek HBM-need cut noise; core shortage evidence still makes ≤55% a low-probability tail.
  - evidence: `CBMidEFVX3lxTE4zTFJVX3h6OGtC`, `CBMinwFBVV95cUxQRE1OOG1aM2U5`, `CBMikwFBVV95cUxQdTBkcTJTZUV4`
  - ⚠ **alert** (low_confidence): confidence 5% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 10%** (-4 pts vs last pulse, from 14%) **⚠ FLAGGED**
  - case: Amkor nearly doubles Peoria to $12B because customer demand fills capacity, explicitly tagged AMKR__TSM__adv_packaging_overflow, while TSMC CoWoS-to-260k-by-2028 spillover and iPhone 18 launch via AAPL__AMKR__osat_packaging both bias quarterly YoY above the ≤15% cap.
  - consensus: AMKR wall shows only +2.7% 0q growth and no recommendation — street still under-weights the overflow AI book.
  - deviation: WEAKENING — live $12B capacity fill and CoWoS spillover make the Apple-cap ≤15% thesis harder to hold.
  - synthesis: Do not lean into ≤15%; overflow edge is active and Apple launches bias the print higher.
  - confidence: Down from 14: $12B Peoria double-down plus repeated CoWoS-spillover tags further cut odds the quarterly print stays ≤15%.
  - evidence: `CBMitgFBVV95cUxNeWIwNmkyUXBy`, `CBMidkFVX3lxTE8tYVhpVFhpdXkz`, `CBMirAFBVV95cUxNTWhvMW41X29D`, `https://www.apple.com/newsro`
  - ⚠ **alert** (low_confidence): confidence 10% <= 10%

- `QCOM-septq-rev-yoy-2026` — **rising · 63%** (+7 pts vs last pulse, from 56%)
  - case: Amazon $60B AI-chip/optical networking milestones are a direct revenue offset; Apple C2 modem on iPhone 18 Pro still cuts AAPL__QCOM__handset_modems, and Samsung 2nm pricing snags softens SAMSUNG__QCOM__handset_socs, but the Amazon book dominates the path above -6.68%.
  - consensus: QCOM wall is hold with 0q rev growth -10.04% framed as structural Apple-modem decline.
  - deviation: STRENGTHENING — $60B Amazon data-center content is a concrete offset the street hold thesis has not absorbed.
  - synthesis: Lean long QCOM into the Nov FYQ4 print; Amazon AI content makes clearing -6.68% the base case despite Apple modem loss and Samsung pricing friction.
  - confidence: Up from 56: multiple independent Amazon $60B confirmations raise the offset probability; Samsung pricing dispute and iPhone 18 C2 modem keep a ceiling on confidence.
  - evidence: `CBMi0AFBVV95cUxOOEZvcHBJTXg4`, `CBMimwFBVV95cUxOR1hDakZxY0lk`, `CBMi5gFBVV95cUxNRGJkWmF1Nk52`, `CBMixwFBVV95cUxQbUE0R1ZOTzBN`, `CBMijAFBVV95cUxNSFV4a2tlWVRG`

- `jobA-20260729T064012Z-C5` — **rising · 85%** (+1 pts vs last pulse, from 84%)
  - case: TSMC/Samsung High-NA/ASML commit tags TSM__KLA__process_control and SAMSUNG__KLA__process_control as live capex tailwinds; KLA Goldman remarks keep growth outlook strong ahead of the Sept-q print.
  - consensus: KLA wall is only buy (not strong_buy) with ~+13.5-25.9% growth — weakest rating in the equipment group.
  - deviation: STRENGTHENING — TSM/Samsung tool commits reinforce the single-customer capex path the claim says is under-priced.
  - synthesis: Sept-q ≥15% remains base case; alpha is still the relative-rating gap vs AMAT/LRCX/ASML.
  - confidence: Up 1pt from 84 on explicit TSM__KLA tagging in the ASML-commit piece; still no hard quarterly number so capped below 90.
  - evidence: `CBMiiwFBVV95cUxPYTZlbzJBNE0x`, `CBMivAFBVV95cUxNcFl4MkhpMnlK`

- `jobA-20260726T115635Z-C4` — **quiet · 29%**
  - case: LRCX lifts 2026 WFE outlook on AI fab strain and ASX posts ATM/August strength plus CoWoS spillover, but no item establishes an LRCX→ASX tool or process supply link.
  - consensus: LRCX wall already prices +52.8% 0q growth and strong_buy; cited_wall deviation anchor is +29%.
  - deviation: UNCHANGED — parallel bullish prints do not wire the missing edge or deliver the quarterly YoY actual.
  - synthesis: No action; edge remains unproven until a direct LRCX-ASX equipment link appears.
  - confidence: Held at prior: outlook lift is directional for LRCX but supplies neither the sealed rev_yoy print nor proof of the LRCX-ASX edge.
  - evidence: `CBMiyAFBVV95cUxPaUduZ2xwWlVE`, `CBMidkFVX3lxTE8tYVhpVFhpdXkz`

- `HBM-zerosum-skhynix-spread-2026` — **rising · 38%** (+8 pts vs last pulse, from 30%)
  - case: KB/Seoul Economic pieces push Samsung HBM share toward ~40% along SAMSUNG__NVDA__hbm and MU__SKHYNIX__hbm_capacity, a zero-sum share shift that can leave SKHYNIX the relative laggard even as HBM4 shortage and <10-day DRAM inventory keep the whole cluster bid.
  - consensus: Wall prices MU/SKHYNIX/SAMSUNG as uniform strong_buy HBM winners with triple-digit growth and elevated targets.
  - deviation: STRENGTHENING — Samsung share-to-40% is the first concrete zero-sum mechanism against SKHYNIX relative return.
  - synthesis: Re-open a modest relative underweight SKHYNIX into the Dec spread; share shift is live even if absolute prices stay firm.
  - confidence: Up from 30: Samsung HBM-share-to-40% headlines supply the zero-sum mechanism the prior window lacked, partially offset by still-tight HBM4 inventory supporting co-rally.
  - evidence: `CBMinwFBVV95cUxQOV9hU1R1ZHpJ`, `CBMidkFVX3lxTE9VZGNtdFZydXN0`, `CBMidEFVX3lxTE4zTFJVX3h6OGtC`, `CBMidEFVX3lxTFBPUmEtWWhVSDB2`

- `AVGO-wafer-hike-multiple-2027` — **falling · 12%** (-2 pts vs last pulse, from 14%)
  - case: Hock Tan says demand already exceeds Broadcom's $115B AI forecast and AI chip revenue grew 221% last quarter, traveling TSM__AVGO__foundry_wafers as pure volume tailwind with no wafer-price or margin-compression signal.
  - consensus: AVGO wall is strong_buy, price ~362 vs mean target ~532, with +93.6% 0q rev growth fully embracing the AI-demand narrative.
  - deviation: WEAKENING — demand-exceeds-forecast and 221% AI growth deepen the positive multiple path away from ≤480.
  - synthesis: Stand down the ≤480 short-multiple; path of least resistance remains higher into 2027.
  - confidence: Down from 14: incremental AVGO demand-exceeds-forecast and 221% AI growth further distance the price path from the ≤480 confirm.
  - evidence: `CBMilwFBVV95cUxPNWw0dUJjemtf`

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
- `SHK-ASML` ASML dir `+` (active)
- `SHK-INTC` INTC dir `+` (active)
- `SHK-ASML__INTC__euv_systems` ASML__INTC__euv_systems dir `+` (active)
- `SHK-TSM__AAPL__leading_edge_soc` TSM__AAPL__leading_edge_soc dir `+` (active)
- `SHK-AAPL` AAPL dir `+` (active)
- `SHK-TSM__INTC__external_foundry` TSM__INTC__external_foundry dir `+` (active)
- `SHK-AVGO__AAPL__wireless_content` AVGO__AAPL__wireless_content dir `+` (active)

**proposed shocks (await operator approval):**
- ASML dir `+` stress 100.1586
- INTC dir `+` stress 79.5051
- ASML__INTC__euv_systems dir `+` stress 46.8854
- TSM__AAPL__leading_edge_soc dir `+` stress 24.6174
- AAPL dir `+` stress 20.9851
- TSM__INTC__external_foundry dir `+` stress 2.0269
- AVGO__AAPL__wireless_content dir `+` stress 1.6477

**propagation rows:**

| name | impact | lands | path |
|---|--:|:--:|---|
| TSM | +0.2295 | 2 | ASML__TSM__euv_systems |
| INTC | +0.2040 | 2 | ASML__INTC__euv_systems |
| AVGO | +0.0981 | 3 | ASML__TSM__euv_systems → TSM__AVGO__foundry_wafers |
| AAPL | +0.0826 | 2 | ASML__TSM__euv_systems → TSM__AAPL__leading_edge_soc |
| AMD | +0.0780 | 2 | ASML__TSM__euv_systems → TSM__AMD__leading_edge_wafers |
| NVDA | +0.0780 | 2 | ASML__TSM__euv_systems → TSM__NVDA__leading_edge_wafers |
| ASML | +0.0288 | 2 | ASML__INTC__euv_systems |
| TSM | +0.0110 | 4 | ASML__INTC__euv_systems → ASML__TSM__euv_systems |
| TSM | +0.2295 | 2 | ASML__TSM__euv_systems |
| AVGO | +0.0981 | 3 | ASML__TSM__euv_systems → TSM__AVGO__foundry_wafers |
| AAPL | +0.0826 | 2 | ASML__TSM__euv_systems → TSM__AAPL__leading_edge_soc |
| AMD | +0.0780 | 2 | ASML__TSM__euv_systems → TSM__AMD__leading_edge_wafers |
| NVDA | +0.0780 | 2 | ASML__TSM__euv_systems → TSM__NVDA__leading_edge_wafers |
| KLA | +0.0196 | 4 | ASML__TSM__euv_systems → TSM__KLA__process_control |
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
| AVGO | +0.2565 | 1 | TSM__AVGO__foundry_wafers |
| AAPL | +0.2160 | 0 | TSM__AAPL__leading_edge_soc |
| AMD | +0.2040 | 0 | TSM__AMD__leading_edge_wafers |
| NVDA | +0.2040 | 0 | TSM__NVDA__leading_edge_wafers |
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
