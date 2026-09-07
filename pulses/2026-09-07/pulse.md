# ADF PULSE — 2026-09-07

- epoch: v1  ·  run (UTC): `2026-09-07T06:27:45Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **9 open sealed claim(s)** (8 ALPHA / 1 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 0 proposed  ·  0 resolved since last pulse  ·  9 assessed (1 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260727T075315Z-C8` | CONSENSUS-HOLDS · graded (shadow-rate) | TSM · TSM__NVDA__leading_edge_wafers,TSM__AVGO__foundry_wafers,TSM__AMD__leading_edge_wafers | TSM September-2026 monthly revenue print, YoY  [>= +40%] | [1] | evidence-accumulating | 8 | Taiwan monthly print ~2026-09-10 | rising · 93% |
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 54 | Taiwan monthly print ~2026-09-10 | rising · 36% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 54 | MU pre-announcement window ~2026-09-10 | falling · 4% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 54 | Taiwan monthly print ~2026-09-10 | falling · 20% |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 69 | Samsung Q3 preliminary guidance ~2026-10-08 | rising · 48% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 69 | Taiwan monthly print ~2026-09-10 | rising · 82% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 84 | Taiwan monthly print ~2026-09-10 | quiet · 30% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 115 | MU pre-announcement window ~2026-09-10 | rising · 38% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 146 | Taiwan monthly print ~2026-09-10 | falling · 18% |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260727T075315Z-C8` — **rising · 93%** (+2 pts vs last pulse, from 91%)
  - case: TSMC record quarter (+35% profit/revenue), Broadcom/NVDA AI wafer pulls along TSM__NVDA__leading_edge_wafers and TSM__AVGO__foundry_wafers, plus ‘20 fabs still short’ and equipment demand +90%, all keep September monthly YoY on track for >=40%.
  - consensus: Street already anchors TSM at ~47% 0q rev growth, strong_buy — the claim is the calibration hold of that view.
  - deviation: STRENGTHENING — successive record prints and capacity-short commentary confirm rather than challenge the >=40% monthly bar.
  - synthesis: Hold as the book’s calibration anchor; September YoY >=40% remains base case.
  - confidence: Nudged up from 91 on the fresh record-quarter and ‘still can’t keep pace’ cluster; only residual risk is a one-month mix quirk.
  - evidence: `CBMijwFBVV95cUxOZUJBVURjbmxm`, `CBMiiAFBVV95cUxNTXFOajBvclRZ`, `CBMioAFBVV95cUxQQXd2SXFQWUps`

- `jobA-20260726T115635Z-C11` — **rising · 36%** (+9 pts vs last pulse, from 27%)
  - case: Multiple items on Nvidia’s $3.5B strategic investment and deepened MediaTek AI-chip partnership raise MediaTek AI silicon demand that would print through TSMC leading-edge wafers, lifting the Sept-2026 monthly YoY path toward >=5%.
  - consensus: Street holds MediaTek as a modest grower (wall rev_growth_0q ~10%, strong_buy) with no wired TSM foundry edge and cited 0q growth at -2.45%.
  - deviation: STRENGTHENING — NVDA capital and co-development give a concrete AI-volume catalyst the unwired MediaTek node previously lacked.
  - synthesis: Treat the missing TSM→MEDIATEK edge as provisionally live; small long-MediaTek into the Oct monthly print is now evidence-supported.
  - confidence: Raised from 27 on the $3.5B NVDA deal cluster; still capped because no actual Sept monthly print or disclosed TSMC wafer share is in-window.
  - evidence: `CBMilAFBVV95cUxOVjBTN0VvU284`

- `jobA-20260727T075315Z-C4` — **falling · 4%** (-2 pts vs last pulse, from 6%) **⚠ FLAGGED**
  - case: Nvidia ‘extreme’ memory pricing headed higher, Micron sold-out HBM3E / 2× capacity plans, and industry inventories <10 days all tighten both HBM and commodity DRAM, pushing MU Q4 GAAP GM away from ≤55% toward the ≥60% fail zone.
  - consensus: Street already bakes MU as the HBM scarcity winner (+349% rev growth, strong_buy, GM expansion implied).
  - deviation: WEAKENING — every in-window item reinforces scarcity pricing, not CXMT-driven commodity margin undershoot.
  - synthesis: Stand down the GM≤55% short; Q4 print is far more likely to clear 60%.
  - confidence: Cut from already-low 6: extreme pricing + sold-out HBM3E leave almost no path to a sub-55% consolidated GM.
  - evidence: `CBMingFBVV95cUxOaFVzaXFqazF2`, `CBMid0FVX3lxTE4wVUlxU2dYQ1RO`, `CBMidkFVX3lxTE9OR0xDZS1qVFF5`, `CBMi4gFBVV95cUxPVTBMVS1nbGpG`
  - ⚠ **alert** (low_confidence): confidence 4% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 20%** (-7 pts vs last pulse, from 27%)
  - case: TSMC–Amkor US advanced-packaging partnership and live CoWoS/substrate squeeze items travel along AMKR__TSM__adv_packaging_overflow, expanding the AI book and pushing AMKR rev YoY toward the >=19.82% fail zone rather than the Apple-capped <=15% confirm.
  - consensus: Street already embeds ~20% AMKR 0q growth on AI-packaging upside (buy, target 76).
  - deviation: WEAKENING — explicit TSMC partnership and packaging-bottleneck overflow make the Apple-mix cap harder to defend.
  - synthesis: Do not lean into <=15%; overflow edge is active and biases the print higher.
  - confidence: Cut from 27 on the TSMC-Amkor partnership and packaging-bottleneck cluster; Apple still ~30% but AI book is no longer latent.
  - evidence: `CBMiowFBVV95cUxPTnRaMXNEMnE1`, `CBMi5gFBVV95cUxQakdJRFhOeEMw`, `CBMixAFBVV95cUxPcjh6QVFrbld6`, `CBMilAFBVV95cUxPZW80dVlfcERE`

- `QCOM-septq-rev-yoy-2026` — **rising · 48%** (+18 pts vs last pulse, from 30%)
  - case: Exclusive Samsung Galaxy S27 Snapdragon testing across three regions and dual top-end S27 Qualcomm wins travel along SAMSUNG__QCOM__handset_socs, supplying the flagship SoC offset that can lift Sept-q YoY above the -6.68% street frame.
  - consensus: Street holds QCOM as hold / structural decliner with 0q rev growth -10% on Apple modem insourcing risk.
  - deviation: STRENGTHENING — concrete multi-region S27 Snapdragon design-wins directly counter the Apple-only bear case.
  - synthesis: Lean long QCOM into the Nov FYQ4 print; Samsung SoC content is now visible enough to clear -6.68%.
  - confidence: Raised from 30 on the S27 Snapdragon exclusives; still mid-range because Apple modem drag and the actual print remain open.
  - evidence: `CBMi4wFBVV95cUxOWjVaZ3ZnbEth`, `CBMitAFBVV95cUxPQ29rakpQVTFs`

- `jobA-20260729T064012Z-C5` — **rising · 82%** (+6 pts vs last pulse, from 76%)
  - case: TSMC equipment demand nearly doubling / CapEx toward $64B travels along TSM__KLA__process_control into KLA’s largest customer, while KLA’s own investor-day buyback and reaffirmed guide keep Sept-q YoY on a >=15% path.
  - consensus: Street rates KLA only buy (weakest of the WFE group) with cited 0q growth ~13.5% despite TSM concentration.
  - deviation: STRENGTHENING — 90% TSMC tool-hunger surge and KLA capital-return actions widen the under-pricing gap the claim targets.
  - synthesis: Sept-q >=15% is base case; the alpha remains the relative-rating gap vs AMAT/LRCX/ASML, not the print itself.
  - confidence: Raised from 76 on the TSMC tool-demand-double cluster plus KLA investor-day confirmation; main residual is timing of process-control vs litho spend.
  - evidence: `CBMigwJBVV95cUxPd20xMFhaaDg2`, `CBMidkFVX3lxTFBHc0ZJUno5RHFr`, `CBMimwJBVV95cUxOY2NESW5HTFFD`, `CBMi5gFBVV95cUxQakdJRFhOeEMw`

- `jobA-20260726T115635Z-C4` — **quiet · 30%**
  - case: TSMC WFE-demand surge items name LRCX alongside peers and ASE shows AI-packaging expansion, but no shipment, tool-PO or design-win link ties LRCX equipment into ASX lines, so the LRCX.rev_yoy observable is unmoved.
  - consensus: Street already prices LRCX as a strong_buy AI-WFE name at ~53% rev growth; ASX is unrated with packaging-overflow only latent.
  - deviation: UNCHANGED — general tool hunger and ASE capacity adds do not instantiate the claimed LRCX→ASX supply edge.
  - synthesis: No action; edge remains unproven until a direct LRCX-ASX tool or process link appears.
  - confidence: Unchanged from prior: still no mechanism evidence that would push LRCX YoY through the 31% confirm threshold via ASX.

- `HBM-zerosum-skhynix-spread-2026` — **rising · 38%** (+15 pts vs last pulse, from 23%)
  - case: Samsung Q2 HBM share to 33% (gap vs SK hynix cut to 17 pp) plus Micron 2× HBM capacity plans travel along MU__SKHYNIX__hbm_capacity / SAMSUNG__NVDA__hbm, eroding SK hynix’s primary-supplier scarcity premium and pushing the SKHYNIX-vs-peers total-return spread toward <=-10%.
  - consensus: Street prices the memory trio as uniform strong_buy HBM winners (MU/SK/SAMSUNG all triple-digit or high growth, targets well above spot).
  - deviation: STRENGTHENING — share-shift and capacity-catch-up evidence make the zero-sum edge observable rather than latent.
  - synthesis: Keep a relative underweight SKHYNIX vs SAMSUNG/MU into the Dec-2026 spread print.
  - confidence: Lifted from 23 on repeated Samsung share-gain and Micron capacity-double items; still modest because absolute HBM pricing remains extreme for all three.
  - evidence: `CBMidkFVX3lxTE52NEoxZFJWOG9Y`, `CBMiqgFBVV95cUxORlVMdFhjV3pt`, `CBMikAFBVV95cUxPUno1ZXZyeFdw`, `CBMi4gFBVV95cUxPVTBMVS1nbGpG`, `CBMiWkFVX3lxTE9ETldHRXJEM0x2`

- `AVGO-wafer-hike-multiple-2027` — **falling · 18%** (-6 pts vs last pulse, from 24%)
  - case: AVGO Q3 AI revenue +221% to $16.7B and Hock Tan’s $230B 2028 AI guide travel along TSM__AVGO__foundry_wafers as pure demand positives that swamp any 2027 wafer-price cost shock, pulling the multiple toward the ≥560 fail zone.
  - consensus: Street is strong_buy AVGO with ~94% rev growth and mean target ~533, treating AI content as strictly margin-accretive.
  - deviation: WEAKENING — record AI prints and multi-year guide reinforce the demand-only narrative the claim tries to short-circuit.
  - synthesis: Stand down the ≤480 short-multiple; path of least resistance remains higher into 2027.
  - confidence: Cut from 24: $16.7B AI quarter and $230B 2028 number dominate; soft-guidance 6% dip is noise vs the fail threshold.
  - evidence: `CBMiiwFBVV95cUxOV1g1S1N4c3BF`, `CBMijgFBVV95cUxNRGgyU3R6ZGNq`, `CBMiwwFBVV95cUxNVjNSSHE4Vl9J`

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
