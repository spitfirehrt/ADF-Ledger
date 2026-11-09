# ADF PULSE — 2026-11-09

- epoch: v1  ·  run (UTC): `2026-11-09T06:48:08Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 1 proposed  ·  0 resolved since last pulse  ·  8 assessed (2 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | -9 | — | quiet · 58% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | -9 | — | falling · 1% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | -9 | — | rising · 48% |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 6 | — | falling · 12% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 6 | Taiwan monthly print ~2026-11-10 | rising · 95% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 21 | Taiwan monthly print ~2026-11-10 | quiet · 14% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 52 | — | falling · 55% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 83 | Taiwan monthly print ~2026-11-10 | quiet · 2% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **quiet · 58%**
  - case: MediaTek deputy GM flags CoWoS packaging as the binding constraint; no September-2026 monthly YoY print appears, so the sealed revenue observable is untouched.
  - consensus: Street holds MEDIATEK 0q revenue growth near -2.45% with strong_buy rating.
  - deviation: UNCHANGED — CoWoS headache item does not move the sealed monthly YoY print.
  - synthesis: Stand down; do not trade a TSM-MEDIATEK allocation story until the sealed September monthly YoY actually posts.
  - confidence: Prior 58 held; still no actual print and packaging chatter is orthogonal to the revenue threshold.
  - evidence: `CBMilgFBVV95cUxQRDRUaFRqWkR2`

- `jobA-20260727T075315Z-C4` — **falling · 1%** **⚠ FLAGGED**
  - case: HBM prices up / Q4 records / demand-beats-supply-through-2030 plus MU holding firm on HBM dominate; Taoyuan halt is labor spat, not CXMT commodity-margin hit to the sealed GM <=55% test.
  - consensus: Street frames MU as pure HBM-scarcity winner (0q growth ~353%, strong_buy).
  - deviation: WEAKENING — sold-out HBM and rising ASP headlines push GM away from the <=55% short.
  - synthesis: GM short is dead; do not fade MU on CXMT/commodity while sold-out HBM headlines dominate.
  - confidence: Prior 1 held; still zero CXMT/commodity evidence and HBM scarcity only strengthens the fails_if path.
  - evidence: `CBMiWEFVX3lxTE1FbENJYWFhYTll`, `CBMiggJBVV95cUxOT3pPX2V1VlRn`
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `jobA-20260729T064012Z-C6` — **rising · 48%** (+6 pts vs last pulse, from 42%)
  - case: MediaTek CoWoS headache and NVDA billions into advanced packaging keep AMKR__TSM__adv_packaging_overflow latent; Apple-mix dominance via AAPL__AMKR__osat_packaging still caps near-term YoY, supporting <=15%.
  - consensus: Street prices AMKR at ~3.6% 0q growth / buy with 66 target, still half-framed as AI packaging beneficiary.
  - deviation: STRENGTHENING — overflow remains capacity-not-revenue this quarter while Apple book stays the binding mix.
  - synthesis: Lean <=15% YoY on the printed mix; treat NVDA packaging billions as forward capacity, not this-quarter overflow revenue.
  - confidence: Lift from 42 on CoWoS-as-headache and NVDA-packaging-bottleneck items that keep overflow latent for the sealed quarter.
  - evidence: `CBMilgFBVV95cUxQRDRUaFRqWkR2`, `CBMikgFBVV95cUxQWXJBTDJKOXhB`

- `QCOM-septq-rev-yoy-2026` — **falling · 12%** (-6 pts vs last pulse, from 18%)
  - case: Handset sales fall 26% to $5.14B, revenue miss, soft profit guide, and 'Apple walks away / December no longer biggest quarter' items travel AAPL__QCOM__handset_modems and SAMSUNG__QCOM__handset_socs straight into the sealed Sept-Q YoY.
  - consensus: Street already frames QCOM as structural decliner (0q growth -11.7%, hold).
  - deviation: WEAKENING — actual handset print and Apple-exit commentary push observable toward fails_if <= -12%.
  - synthesis: Cut conviction further on >-6.7% Sept-Q; print risk is now skewed to the fails_if side.
  - confidence: Cut from 18 on the 26% handset drop and Apple-walks-away items that raise odds of <= -12% YoY.
  - evidence: `CBMikwFBVV95cUxNdWR6RG1uU2tD`, `CBMivwFBVV95cUxNSUJqcTZCQ1Zt`, `CBMi7wFBVV95cUxQNWxSV2h1WTFf`, `CBMitAFBVV95cUxOVjRWZDhfZ1BE`

- `jobA-20260729T064012Z-C5` — **rising · 95%** (+1 pts vs last pulse, from 94%)
  - case: KLA Q1 earnings beat + upgraded guidance and S&P upgrade to A on AI demand directly support the sealed Sept-Q >=15% YoY via TSM__KLA__process_control concentration.
  - consensus: Street gives KLA the weakest equipment rating (buy, ~220 target) vs strong_buy peers despite 0q growth ~43%.
  - deviation: STRENGTHENING — beat/raise and AI-demand upgrade move the revenue test toward confirm.
  - synthesis: Treat >=15% Sept-Q as confirmed; residual alpha is rating/multiple catch-up, not the revenue test.
  - confidence: Nudge from 94 on the explicit Q1 beat and upgraded guidance item that locks the >=15% path.
  - evidence: `CBMieEFVX3lxTFBxaVFTc2M4cDhr`, `CBMijwFBVV95cUxNR3dBeWJCUDZQ`

- `jobA-20260726T115635Z-C4` — **quiet · 14%**
  - case: LRCX $25B buyback/dividend cluster dominates the window; zero items link LRCX equipment supply to ASX packaging, so the claimed edge and rev-YoY observable stay unmoved.
  - consensus: Street prices LRCX at +61.7% 0q growth / strong_buy with 364 target.
  - deviation: UNCHANGED — capital-return headlines do not speak to an LRCX-ASX packaging-equipment edge or the 31% YoY test.
  - synthesis: Remain stood down on any LRCX-ASX edge trade; observable still unlinked to the claimed mechanism.
  - confidence: Prior 14 held; buyback noise adds no path to the sealed rev-YoY threshold.

- `HBM-zerosum-skhynix-spread-2026` — **falling · 55%** (-13 pts vs last pulse, from 68%)
  - case: SK hynix half of 2027/28 capacity already contracted + HBM prices up 121% / demand-through-2030 + Q4 record-revenue call co-extend wallets along SKHYNIX__NVDA__hbm and MU__SKHYNIX__hbm_capacity; MU Taoyuan halt is labor, not share shift against SKH.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as uniform HBM rally (strong_buy, triple-digit growth).
  - deviation: WEAKENING — contracted forward capacity and rising HBM ASP point to co-extension, not zero-sum underperformance of SKHYNIX.
  - synthesis: Dial back the SKHYNIX underperformance lean; window shows co-extension of HBM wallets, not zero-sum share shift.
  - confidence: Cut from 68 on contracted 2027/28 capacity and HBM price-up items that reduce odds of SKH lagging the MU/SAMSUNG mean by 10 pts.
  - evidence: `CBMitgFBVV95cUxQNGZaQmpNWkw2`, `CBMiWEFVX3lxTE1FbENJYWFhYTll`, `CBMiggJBVV95cUxOT3pPX2V1VlRn`

- `AVGO-wafer-hike-multiple-2027` — **quiet · 2%** **⚠ FLAGGED**
  - case: TSMC advanced-memory / 3D-DRAM mull items and Apple M5 launch travel TSM__NVDA and TSM__AAPL edges; nothing transmits a 2027 wafer-price cost shock into AVGO multiple via TSM__AVGO__foundry_wafers.
  - consensus: Street holds AVGO strong_buy / ~533 target with 0q growth ~94%.
  - deviation: UNCHANGED — AI-content demand narrative still dominates; no wafer-hike margin compression visible.
  - synthesis: Keep the Jan-2027 <=480 short stood down; live transmission is AI content, not wafer-cost multiple compression.
  - confidence: Prior 2 held; no new cost-shock evidence and price already far below fails_if.
  - ⚠ **alert** (low_confidence): confidence 2% <= 10%

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
- TSM__AAPL__leading_edge_soc dir `+` stress 9.8691

## §5 — RESOLUTIONS (since last pulse)

_no resolutions since the last pulse._

## §6 — CHECKPOINT OUTCOMES (since last pulse)

_Raw comparisons against the frozen reference. A comparison, **not a grade** — claims are graded only at resolution._

_no checkpoint passed since the last pulse._

---
_Tiers are stated: §1 is graded; §2/§3 are ungraded. Internal machinery (checkup evidence, amendment queue, stress-ledger internals, judge/repair rationales) never ships. Map changes reach buyers as epoch-boundary changelogs._
