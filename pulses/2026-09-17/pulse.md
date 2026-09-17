# ADF PULSE — 2026-09-17

- epoch: v1  ·  run (UTC): `2026-09-17T02:29:14Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 1 proposed  ·  1 resolved since last pulse  ·  8 assessed (3 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 44 | Taiwan monthly print ~2026-10-10 | rising · 44% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 44 | MU fiscal-Q4 FY26 earnings ~2026-09-24 | falling · 5% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 44 | Taiwan monthly print ~2026-10-10 | falling · 8% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 59 | Samsung Q3 preliminary guidance ~2026-10-08 | rising · 70% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 59 | Taiwan monthly print ~2026-10-10 | rising · 87% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 74 | Taiwan monthly print ~2026-10-10 | quiet · 28% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 105 | MU fiscal-Q4 FY26 earnings ~2026-09-24 | rising · 41% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 136 | Taiwan monthly print ~2026-10-10 | falling · 9% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **rising · 44%** (+9 pts vs last pulse, from 35%)
  - case: MediaTek Dimensity 9600 Pro debuts as first phone SoC on TSMC 2nm and beats QCOM to market; digitimes flags MediaTek among customers shifting tight TSMC 3/2nm/CoWoS capacity — product-cycle and foundry-allocation evidence supports a Sept YoY print clearing +5%.
  - consensus: MEDIATEK wall is strong_buy with modest ~10.6% rev growth; cited_wall still anchors the fail bar at -2.45% YoY.
  - deviation: STRENGTHENING — first-to-2nm flagship plus explicit TSMC capacity allocation make the unwired TSM→MEDIATEK leading-edge link commercially visible this window.
  - synthesis: Hold for the ~Oct 10 MediaTek September monthly; 2nm launch raises odds the print clears +5% vs the -2.45% fail bar.
  - confidence: Raised from 35 on concrete 2nm design-win and capacity-shift items; still capped because the sealed observable is the not-yet-released Sept monthly print.
  - evidence: `CBMiigFBVV95cUxPekM4MUlNWGxZ`, `CBMicEFVX3lxTE1EQ3JlMUhIUmhP`, `CBMidkFVX3lxTE1Vam9NUWpWU2RT`, `CBMihAFBVV95cUxQMWlJSzVXejJI`, `CBMidkFVX3lxTE5JeE9IekdkdWoz`

- `jobA-20260727T075315Z-C4` — **falling · 5%** **⚠ FLAGGED**
  - case: Multiple items frame MU as ramping HBM production into NVDA (MU__NVDA__hbm) with bullish stock implications; no CXMT commodity-DRAM margin evidence appears — HBM mix supports GM well above the ≤55% short threshold.
  - consensus: MU wall strong_buy with extreme ~349% rev growth baked as pure HBM-scarcity winner.
  - deviation: WEAKENING — window reinforces the HBM-winner frame and supplies zero commodity-DRAM undershoot evidence against the GM print.
  - synthesis: Keep the GM≤55% short stood down; Q4 print far more likely to clear 60% on HBM ramp mix.
  - confidence: Unchanged at 5; HBM-ramp features dominate and still no CXMT/commodity margin data to revive the short.
  - evidence: `CBMiggJBVV95cUxQTmdVV050NE5Y`, `CBMilwFBVV95cUxPdUVHSURiR21X`, `CBMimAFBVV95cUxPbXBfcmJzWUpa`, `CBMimgFBVV95cUxPY1Jnb251OXgz`
  - ⚠ **alert** (low_confidence): confidence 5% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 8%** (-2 pts vs last pulse, from 10%) **⚠ FLAGGED**
  - case: Amkor announces Phase 2 Arizona advanced packaging/test campus, expanding investment to $12B, explicitly tagged AMKR__TSM__adv_packaging_overflow; digitimes CoWoS tightness and ASE/SPIL Arizona race reinforce overflow AI packaging as the near-term growth driver over the 29.8% Apple seasonal book.
  - consensus: AMKR wall shows recommendation none and only ~2.7% rev growth; cited_wall still at +19.8%.
  - deviation: WEAKENING — $12B Arizona Phase 2 and live CoWoS-overflow framing push the street toward AI-packaging principal, away from the Apple-cap thesis.
  - synthesis: Do not lean into ≤15%; overflow edge is active and Arizona Phase 2 biases the next print higher.
  - confidence: Cut from 10 on the $12B Phase 2 announcement directly on AMKR__TSM__adv_packaging_overflow; Apple-mix cap thesis has no supporting item this window.
  - evidence: `CBMi0AFBVV95cUxQTzRPY0kxZWpB`, `CBMigwJBVV95cUxPQ2RXdXo4XzVv`, `CBMihAFBVV95cUxQMWlJSzVXejJI`, `CBMi2wFBVV95cUxPdWtEYU8zcFNs`
  - ⚠ **alert** (low_confidence): confidence 8% <= 10%

- `QCOM-septq-rev-yoy-2026` — **rising · 70%** (+7 pts vs last pulse, from 63%)
  - case: Amazon up-to-$60B chip deal plus equity stake opens a new AI-content growth avenue that offsets Apple modem risk; iPhone 18 Pro Max still ships Qualcomm modem in the US (AAPL__QCOM__handset_modems), while MediaTek's 2nm beat is handset-SoC share noise not Sept-q revenue destruction.
  - consensus: QCOM wall is hold with rev growth -10.0%; cited_wall anchors structural decline at -6.68%.
  - deviation: STRENGTHENING — Amazon AI content plus delayed Apple modem insourcing on iPhone 18 Pro Max US directly challenge the structural-decliner frame into the FYQ4 print.
  - synthesis: Lean long QCOM into the Nov FYQ4 print; clearing -6.68% is now the base case on Amazon content and retained US modem dollars.
  - confidence: Raised from 63 on quantified Amazon $60B deal and explicit iPhone 18 Pro Max Qualcomm-modem retention; MediaTek 2nm beat is the main residual drag.
  - evidence: `CBMilgFBVV95cUxOSV9XTDVGbk42`, `CBMijgFBVV95cUxPZmNVWkpPUF94`, `CBMihgFBVV95cUxNazAtR20zM0hu`, `CBMiwgFBVV95cUxPYUVlUHNEamFf`

- `jobA-20260729T064012Z-C5` — **rising · 87%** (+2 pts vs last pulse, from 85%)
  - case: TSMC 2nm capacity aimed at 110k wpm by H2 2027 and 3nm boost to 210k wpm travel TSM__KLA__process_control as leading-edge process-control demand; KLA backlog +60% and GS conference growth outlook stay strong into the Sept-q print.
  - consensus: KLA wall is only buy (weakest equipment rating) with ~25.9% growth; cited_wall bar at 13.5%.
  - deviation: STRENGTHENING — explicit N2/N3 capacity ramps tagged to TSM__KLA__process_control plus backlog confirmation widen the under-priced single-customer tailwind.
  - synthesis: Sept-q ≥15% remains base case; alpha is still the relative-rating gap vs AMAT/LRCX/ASML.
  - confidence: Up from 85 on TSMC 2nm-outpaces-3nm capacity math explicitly wired to TSM__KLA__process_control and backlog support; Form-4/144 noise is immaterial.
  - evidence: `CBMidkFVX3lxTE9BUlJDWF82Ny1h`, `CBMiuAFBVV95cUxQeTNyNUxHYjJS`, `CBMitgFBVV95cUxNbGtEbWl0S0x0`

- `jobA-20260726T115635Z-C4` — **quiet · 28%** (-1 pts vs last pulse, from 29%)
  - case: LRCX sold-out demand and India silicon-plant capex are generic WFE positives; ASX Arizona/SPIL packaging headlines run in parallel — no item establishes an LRCX→ASX advanced-packaging equipment supply link or moves LRCX rev YoY vs the 31% threshold.
  - consensus: LRCX wall is strong_buy with ~52.8% rev growth; cited_wall deviation bar sits at +29%.
  - deviation: UNCHANGED — still no observable transmission path from LRCX tools into ASX packaging spend.
  - synthesis: No action; edge remains unproven until a direct LRCX-ASX equipment order or disclosure appears.
  - confidence: Nudged -1 from 29; India/sold-out items raise LRCX absolute but add zero weight to the sealed LRCX-ASX edge hypothesis.

- `HBM-zerosum-skhynix-spread-2026` — **rising · 41%** (+3 pts vs last pulse, from 38%)
  - case: Samsung restructures Cheonan to prioritize HBM, shifts manufacturing to AI-HBM, and is reported to edge SK hynix on HBM4 earnings outlook — share pressure travels MU__SKHYNIX__hbm_capacity and SAMSUNG__NVDA__hbm; SK's Intel-Ohio talks are capacity-additive but do not reverse the HBM4 share tilt.
  - consensus: Memory cluster priced as uniform strong_buys (MU/SK/Samsung all multi-bagger targets); cited SK target still elevated vs Samsung agree.
  - deviation: STRENGTHENING — explicit Samsung-over-SK HBM4 ranking and Cheonan HBM reallocation make the zero-sum edge live inside the cluster.
  - synthesis: Keep a modest relative underweight SKHYNIX into the Dec spread; HBM4 share shift is the mechanism even if absolute memory prices stay firm.
  - confidence: Up from 38 on Samsung-edges-SK HBM4 and Cheonan priority items; SK-Intel US fab talks and co-moving selloffs cap the move.
  - evidence: `CBMiiAFBVV95cUxQQ0dFWmIyc1kz`, `CBMixgFBVV95cUxQb3JjVEVROUQ0`, `CBMijwFBVV95cUxON1pyWGU4THhz`

- `AVGO-wafer-hike-multiple-2027` — **falling · 9%** (-3 pts vs last pulse, from 12%) **⚠ FLAGGED**
  - case: Hock Tan says demand already exceeds the $115B AI forecast and guides toward $230B by 2028; $350B AI order lock-in and Anthropic named as next custom-silicon customer after Google travel along TSM__AVGO__foundry_wafers as pure volume/pricing power, not margin compression from any 2027 wafer hike.
  - consensus: AVGO wall strong_buy, target ~532, rev growth ~94%; cited target 525.44.
  - deviation: WEAKENING — AI backlog and customer adds dominate any latent foundry-cost shock narrative into the 2027 multiple window.
  - synthesis: Keep the ≤480 short-multiple stood down; path of least resistance remains higher into Jan-2027 resolution.
  - confidence: Cut from 12 on stacked demand-exceeds-forecast and multi-customer AI order items with zero counter-evidence of wafer-price margin hit.
  - evidence: `CBMilgFBVV95cUxOS3E3dEZKMHJZ`, `CBMiXEFVX3lxTFBKaEFLdG1TUjBp`, `CBMiqAFBVV95cUxOcndGVll3SDgy`, `CBMimAFBVV95cUxNVDFFalZremRS`
  - ⚠ **alert** (low_confidence): confidence 9% <= 10%

## §2 — WATCH (warming up)

_Ungraded; promotion-before-resolution only._

_no active watches._

## §3 — TRACKED (inventory)

_Ungraded, tracked for transparency._
- `jobA-20260727T075315Z-C5` — Equipment cluster priced idiosyncratically strong_buy but is one correlated 2Q-lagged capex bet.
- `jobA-20260727T075315Z-C6` — AAPL inverted target reads ex-growth, missing a TSM-locked refresh + Broadcom content lock (frame inversion).
- `jobA-20260729T064012Z-C12` — AAPL priced ex-growth (PT 318.8 < price 333, only large-cap set to fall); an M5 Mac/iPhone hardware upcycle on TSM N2 sole-source plus refreshed Broadcom connectivity content.

## §4 — SHOCKS & EXPOSURES

**proposed shocks (await operator approval):**
- TSM__INTC__external_foundry dir `+` stress 1.4332

## §5 — RESOLUTIONS (since last pulse)
- `jobA-20260727T075315Z-C8`: **CONFIRM** — observable met (as of 2026-09-15; res-sha f782493f6c04fe12)

## §6 — CHECKPOINT OUTCOMES (since last pulse)

_Raw comparisons against the frozen reference. A comparison, **not a grade** — claims are graded only at resolution._

_no checkpoint passed since the last pulse._

---
_Tiers are stated: §1 is graded; §2/§3 are ungraded. Internal machinery (checkup evidence, amendment queue, stress-ledger internals, judge/repair rationales) never ships. Map changes reach buyers as epoch-boundary changelogs._
