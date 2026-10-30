# ADF PULSE — 2026-10-30

- epoch: v1  ·  run (UTC): `2026-10-30T05:37:22Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 1 active / 2 proposed  ·  0 resolved since last pulse  ·  8 assessed (2 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 1 | — | quiet · 56% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 1 | — | falling · 1% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 1 | — | rising · 18% |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 16 | QCOM fiscal-Q4 FY26 earnings ~2026-11-05 | falling · 28% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 16 | Taiwan monthly print ~2026-11-10 | rising · 92% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 31 | Taiwan monthly print ~2026-11-10 | quiet · 14% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 62 | — | rising · 82% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 93 | Taiwan monthly print ~2026-11-10 | falling · 2% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **quiet · 56%**
  - case: No MediaTek September-2026 Taiwan monthly revenue print appeared; TSM CoWoS hike tape and the Nvidia-MediaTek NVLink item do not move the sealed YoY observable.
  - consensus: Street holds MEDIATEK 0q revenue growth near -2.45% with a strong_buy rating.
  - deviation: UNCHANGED — still waiting on the sealed monthly print; no mechanism this window.
  - synthesis: Stand by for the ~Oct 10 monthly print; do not trade TSM allocation or NVLink color into this observable.
  - confidence: Unchanged: no print and no new bias either way on the sealed September YoY.

- `jobA-20260727T075315Z-C4` — **falling · 1%** **⚠ FLAGGED**
  - case: SK hynix/Samsung HBM sold-out and shortage-through-2030 tape plus ‘Micron is a winner too’ along MU__SKHYNIX__hbm_capacity and MU__NVDA__hbm bury any CXMT commodity-DRAM margin undershoot into the sealed MU GM print.
  - consensus: Street treats MU as an HBM-scarcity strong_buy with extreme 0q revenue growth.
  - deviation: WEAKENING — peer HBM allocation and shortage headlines leave no room for a <=55% GM fade.
  - synthesis: GM short is dead; do not fade MU on commodity-DRAM/CXMT while HBM sold-out headlines dominate.
  - confidence: Pinned at floor: still no MU GM actual and HBM scarcity tape only intensifies against the short.
  - evidence: `CBMigAFBVV95cUxPaUplZVQtYWJD`
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `jobA-20260729T064012Z-C6` — **rising · 18%** (+17 pts vs last pulse, from 1%)
  - case: Amkor Q3 miss with communications weakness along AAPL__AMKR__osat_packaging/QCOM__AMKR__osat_packaging caps the print even while AMKR__TSM__adv_packaging_overflow stays live via CoWoS hike/tightness tape.
  - consensus: Street still embeds ~20% AMKR 0q growth as if CoWoS overflow were the dominant book.
  - deviation: STRENGTHENING — miss plus communications weakness re-centers the Apple/handset mix as the binding constraint on YoY.
  - synthesis: Re-open a lean on <=15% YoY: consumer-packaging miss is printing even with overflow headlines active.
  - confidence: Up from 1 on Q3 miss/communications weakness, still capped because overflow edge remains live and prior path had failed.
  - evidence: `CBMiqwFBVV95cUxQNGtlV1JsT3Yy`, `CBMi7AFBVV95cUxQd1hGSzVJT1dD`, `CBMikgFBVV95cUxNN3UtckREdlJ1`

- `QCOM-septq-rev-yoy-2026` — **falling · 28%** (-14 pts vs last pulse, from 42%)
  - case: Qualcomm handset revenue falls 20% with global layoff pledge and ‘performance short of expectations’ into a decline-expected Q4 print; SAMSUNG__QCOM__handset_socs offers no offset as Samsung mobile/networks lose money.
  - consensus: Street already frames QCOM as hold with negative 0q revenue growth on Apple modem risk.
  - deviation: WEAKENING — handset -20% and pre-announce job cuts push the sealed Sept-Q YoY toward the fail zone rather than a beat of -6.7%.
  - synthesis: Cut conviction on >-6.7% Sept-Q; handset collapse dominates any Samsung SoC or price-hike offset into the print.
  - confidence: Down from 42: explicit handset -20% and decline preview outweigh residual Samsung/Anduril color.
  - evidence: `CBMitAFBVV95cUxOMnNnb2ZYcUxw`, `CBMilgFBVV95cUxON2U2NGJoLWEx`, `CBMinwFBVV95cUxPaVJtYU16aExH`, `CBMizwFBVV95cUxQb09LMUZPR3df`

- `jobA-20260729T064012Z-C5` — **rising · 92%** (+12 pts vs last pulse, from 80%)
  - case: KLA Q1 FY2027 record $4.14B revenue with explicit ~29% YoY rise, 46% op margin and Dec guide $4.7B directly clears the sealed >=15% observable; TSM__KLA__process_control and Samsung capex lift reinforce the customer tailwind.
  - consensus: Street still rates KLA only buy with the softest upside in the WFE group versus strong_buy peers.
  - deviation: STRENGTHENING — printed 29% YoY and raised guide convert the under-priced TSM-concentration thesis into a near-resolved beat.
  - synthesis: Treat Sept-Q >=15% as effectively confirmed on the $4.14B/29% print; rating lag is the residual alpha, not the revenue test.
  - confidence: Up from 80: explicit 29% YoY and record quarter remove most resolution risk on the sealed threshold.
  - evidence: `CBMiXkFVX3lxTE1WSFVtc1p3WkFp`, `CBMibkFVX3lxTE1hOW5SeUoyVkxK`, `CBMijgFBVV95cUxQM2Fuc0ZJeUpH`, `CBMidkFVX3lxTE5PWHprbGZQNzV3`

- `jobA-20260726T115635Z-C4` — **quiet · 14%**
  - case: LRCX Q1 beat and equipment rally on SK Hynix shortage, plus ASX record Q3/LEAP expansion, print in parallel but no LRCX→ASX advanced-packaging equipment transmission is evidenced.
  - consensus: Street already prices LRCX strong_buy with elevated 0q revenue growth and ASX without a formal recommendation.
  - deviation: UNCHANGED — dual-node strength does not wire or test the missing LRCX-ASX edge.
  - synthesis: Remain stood down on any LRCX-ASX edge trade; observable still unlinked to the claimed mechanism.
  - confidence: Flat vs prior: beat/rally helps LRCX optics but supplies no YoY figure or edge proof toward >=31%.
  - evidence: `CBMiiAJBVV95cUxPR0JCLWVDVDRU`, `CBMi4gFBVV95cUxPVFRGMk5VUmZu`, `CBMidkFVX3lxTE1mbldNbk40a2F4`

- `HBM-zerosum-skhynix-spread-2026` — **rising · 82%** (+4 pts vs last pulse, from 78%)
  - case: Samsung triples 3Q HBM4 sales, sells out 2027 HBM and is poised to top SK hynix in HBM revenue (Q4 share near 40%) while SK hynix posts record profit but sold-out-through-2029; share shift travels MU__SKHYNIX__hbm_capacity and SAMSUNG__NVDA__hbm toward a negative SKHYNIX relative spread.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as a uniform strong_buy HBM supercycle with no relative loser.
  - deviation: STRENGTHENING — Samsung HBM share reclaim vs SK hynix is the first hard zero-sum print on the sealed edges.
  - synthesis: Lean the <=-10% SKHYNIX-vs-MU/SAMSUNG total-return spread; Samsung share gain is the live relative-loser mechanism.
  - confidence: Up from 78 on Samsung HBM revenue-share reclaim and 2027 sell-out vs still-uniform peer rally risk.
  - evidence: `CBMiekFVX3lxTE85RFVkSmpBbnJX`, `CBMidkFVX3lxTE5HaWxzdTdoalYy`, `CBMivwFBVV95cUxQMFlDQThWbDlv`, `CBMigAFBVV95cUxPaUplZVQtYWJD`

- `AVGO-wafer-hike-multiple-2027` — **falling · 2%** **⚠ FLAGGED**
  - case: Broadcom-organized $63bn Anthropic financing and stock-climbing tape dominate along TSM__AVGO__foundry_wafers; CoWoS packaging-hike items are not a 2027 wafer-price cost shock to AVGO margins.
  - consensus: Street holds AVGO strong_buy with mean target well above spot and treats AI demand as strictly positive.
  - deviation: WEAKENING — demand-financing headlines overwhelm any latent wafer-hike margin path into the <=480 price observable.
  - synthesis: Keep the Jan-2027 <=480 short stood down; Anthropic capacity financing is the live transmission, not a wafer-cost multiple crush.
  - confidence: Unchanged low: no wafer-hike print and $63bn deal tape further distances price from confirming the short.
  - evidence: `CBMi-gFBVV95cUxQQ1hSSERYZERB`, `CBMi4wFBVV95cUxQT19QeEZGekZM`, `CBMikgFBVV95cUxNN3UtckREdlJ1`
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

**active / approved shocks:**
- `SHK-AAPL` AAPL dir `+` (active)

**proposed shocks (await operator approval):**
- AAPL dir `+` stress 17.6771
- TSM__AAPL__leading_edge_soc dir `+` stress 12.33

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
