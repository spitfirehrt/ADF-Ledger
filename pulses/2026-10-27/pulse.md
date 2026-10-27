# ADF PULSE — 2026-10-27

- epoch: v1  ·  run (UTC): `2026-10-27T09:37:55Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 2 proposed  ·  0 resolved since last pulse  ·  8 assessed (3 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 4 | — | quiet · 56% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 4 | — | falling · 1% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 4 | — | falling · 1% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 19 | QCOM fiscal-Q4 FY26 earnings ~2026-11-05 | falling · 42% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 19 | Taiwan monthly print ~2026-11-10 | quiet · 80% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 34 | Taiwan monthly print ~2026-11-10 | falling · 14% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 65 | — | rising · 78% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 96 | Taiwan monthly print ~2026-11-10 | falling · 2% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **quiet · 56%**
  - case: MediaTek record-quarter headline is not the sealed September-2026 Taiwan monthly YoY print; TSM CoWoS/revenue items do not move MEDIATEK.revenue_growth.
  - consensus: Street holds MediaTek strong_buy with 0q revenue growth ~0.145 and the cited wall print at -0.0245 as the fade baseline.
  - deviation: UNCHANGED — no September monthly revenue actual arrived this window.
  - synthesis: Stand by for the ~Oct 10 Taiwan monthly print; ignore TSM allocation and MediaTek quarterly color for this observable.
  - confidence: Unchanged from prior: still pre-print, no mechanism moved the sealed monthly YoY.

- `jobA-20260727T075315Z-C4` — **falling · 1%** **⚠ FLAGGED**
  - case: Micron AI memory sold out through 2026 into 2028 and CEO tight-supply reaffirmation dominate MU__NVDA__hbm / MU__SKHYNIX__hbm_capacity; CXMT is only a controversy tag, not a commodity-DRAM margin hit into the Q4 GM print.
  - consensus: Street frames MU as strong_buy HBM-scarcity winner with extreme 0q growth (~3.5x) and elevated EPS.
  - deviation: WEAKENING — sold-out/tight-supply tape makes <=55% GM almost unreachable versus the >=60% fail path.
  - synthesis: GM short is dead; do not fade MU on commodity-DRAM/CXMT risk while HBM allocation headlines dominate.
  - confidence: Prior 1 unchanged: no commodity-margin evidence; sold-out-through-2028 further buries the short.
  - evidence: `CBMioAFBVV95cUxPLTF2QmkzRUVo`, `CBMi0gFBVV95cUxPbm1SNF8yYlFF`, `CBMidkFVX3lxTE12dURBaUlRbi1n`
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 1%** **⚠ FLAGGED**
  - case: Amkor record $1.99B Q3, +400 bps GM on AI packaging, Q4 $1.9-2.0B guide and $1.3B Nvidia Korea expansion (plus 300% advanced-packaging capacity plan) light AMKR__TSM__adv_packaging_overflow hard; Apple-book cap thesis is overwhelmed.
  - consensus: Street has AMKR buy with modest 0q growth (~0.067 cited wall was ~0.20) still framed more consumer-OSAT than AI principal.
  - deviation: WEAKENING — live Nvidia overflow and record AI-packaging quarter push YoY well away from the <=15% short.
  - synthesis: Do not lean <=15%; overflow edge is live and the short trajectory has already failed.
  - confidence: Prior 1 held: record AI-packaging print and $1.3B NVDA deal leave no path to confirm the revenue short.
  - evidence: `CBMiXkFVX3lxTFBuSU5VZ19KR2tR`, `CBMiaEFVX3lxTE1NbGVTSG4waWdq`, `CBMihAFBVV95cUxPRTFUak1UZGY4`, `CBMiigFBVV95cUxNMlRtZ1p2YWxR`, `CBMinwFBVV95cUxQaWRhZjBEaGM0`
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `QCOM-septq-rev-yoy-2026` — **falling · 42%** (-6 pts vs last pulse, from 48%)
  - case: Samsung Galaxy production cuts and Exynos 2700 beating Snapdragon travel SAMSUNG__QCOM__handset_socs as demand/share loss; November performance-based layoff stack adds internal stress; hyperscaler ASIC order color is too thin to offset the Sept-Q handset book.
  - consensus: Street holds QCOM as hold with 0q growth ~-0.10 and frames structural modem/SoC decline.
  - deviation: WEAKENING — handset-cut and Exynos-share items raise odds the Sept-Q print sits at or below the -6.7% wall rather than beating it.
  - synthesis: Trim conviction on >-6.7% Sept-Q beat; handset and competitive SoC pressure dominate into the print.
  - confidence: Prior 48 cut on Galaxy production slashes plus Exynos-outscore cluster; DC-chip order headline only partial offset.
  - evidence: `CBMikwFBVV95cUxOUzJXRDljMjI5`, `CBMiV0FVX3lxTE9KZmV1WkJ1ZkVu`, `CBMiowFBVV95cUxNamVrTTBka1JG`, `CBMizgFBVV95cUxQV3ppRWRzak9j`

- `jobA-20260729T064012Z-C5` — **quiet · 80%** (-6 pts vs last pulse, from 86%)
  - case: KLA -9.5% sigma drop and peer WFE selloff are price/multiple moves, not the Sept-Q revenue actual; TSM record revenue and raised 2026 forecast still support TSM__KLA__process_control but no KLA quarter print landed.
  - consensus: Street rates KLA buy with the weakest equipment upside and 0q growth ~0.26 / cited ~0.135 vs claim >=15%.
  - deviation: UNCHANGED — equity weakness without a revenue miss leaves the TSM-capex confirmation path intact but untested this window.
  - synthesis: Hold Sept-Q >=15% as base case on TSM spend; do not read the WFE tape washout as the sealed revenue observable.
  - confidence: Prior 86 trimmed on KLA/AMAT/LRCX washout and MS target cut; mechanism still TSM capex, no contrary revenue actual.
  - evidence: `CBMioAFBVV95cUxNMmUxekRsOUYt`, `CBMirwFBVV95cUxNNUF4Z0lFTlpl`, `price_anomaly:KLA:2026-10-23`, `CBMinwFBVV95cUxNbHE1RXhMa0Fw`, `CBMiqAFBVV95cUxQNWdsakpJVzdM`

- `jobA-20260726T115635Z-C4` — **falling · 14%** (-4 pts vs last pulse, from 18%)
  - case: LRCX record revenue/earnings is offset by cautious Dec guide, China drop and supply-constraint ceiling (TradingView/Seeking Alpha/Yahoo); no LRCX→ASX packaging-tool disclosure appears, so the >=31% YoY path stays impaired.
  - consensus: Street has LRCX strong_buy with 0q growth ~0.62 and the claim cites a +29% consensus hurdle.
  - deviation: WEAKENING — supply-snag and China-revenue headlines pull the print toward the <29% fail band rather than a clean >=31% beat.
  - synthesis: Remain stood down on any LRCX-ASX edge trade; observable still tracking toward fail.
  - confidence: Prior 18 cut on supply-cap/China-drop stack; record-revenue print alone does not clear the 31% bar without a disclosed YoY figure.
  - evidence: `CBMi9wFBVV95cUxPQS15c2RCMXVl`, `CBMipwFBVV95cUxNYkZEMUZsNGE0`, `CBMioAFBVV95cUxNMmUxekRsOUYt`, `CBMie0FVX3lxTFBtSlJ6QzlEVHF0`

- `HBM-zerosum-skhynix-spread-2026` — **rising · 78%** (+4 pts vs last pulse, from 74%)
  - case: Bernstein/Korea Herald: Samsung topples or may overtake SK hynix in HBM revenue and commands premium HBM prices; travels MU__SKHYNIX__hbm_capacity + SAMSUNG__NVDA__hbm vs SKHYNIX__NVDA__hbm while MU sold-out-through-2028 strengthens the MU leg of the spread.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as a uniform strong_buy HBM rally with elevated targets across the cluster.
  - deviation: STRENGTHENING — share-shift and premium-price items make the zero-sum edge visible and favor SKHYNIX relative underperformance.
  - synthesis: Lean the <=-10% SKHYNIX-vs-MU/SAMSUNG total-return spread; relative loser is printing on board edges.
  - confidence: Prior 74 raised on Samsung HBM-revenue overtake plus MU sold-out confirmation; still open to cluster-wide squeeze into year-end.
  - evidence: `CBMidkFVX3lxTFBmb002Qkxjd0Zv`, `CBMidEFVX3lxTE1RY2d5UVZ6N3BH`, `CBMiV0FVX3lxTE1faVd5eWpUd3R1`, `CBMioAFBVV95cUxPLTF2QmkzRUVo`, `CBMidkFVX3lxTE12dURBaUlRbi1n`

- `AVGO-wafer-hike-multiple-2027` — **falling · 2%** (-1 pts vs last pulse, from 3%) **⚠ FLAGGED**
  - case: $63B bank/Blackstone SPV financing Broadcom AI chips for Anthropic (WSJ/Reuters/Investing) is pure demand support along TSM__AVGO__foundry_wafers; CoWoS ~20% packaging-hike chatter is not a 2027 wafer-price cost shock into AVGO.price.
  - consensus: Street is strong_buy AVGO with mean target ~530 and 0q growth ~0.94; claim needs price <=480 by Jan-2027 as margin-compression.
  - deviation: WEAKENING — mega financing and CEO-sealed Anthropic lease structure push the multiple away from the short threshold.
  - synthesis: Keep the Jan-2027 <=480 short stood down; demand financing dominates and no wafer-hike transmission printed.
  - confidence: Prior 3 cut further: $63B SPV is the opposite of margin-compression evidence into the price observable.
  - evidence: `CBMioAFBVV95cUxNbkxxMllvRjN2`, `CBMi0gFBVV95cUxNY2ZrV3U0ekU5`, `CBMifkFVX3lxTFB6U1I2V0FqY1R2`
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
- AAPL dir `+` stress 11.946
- TSM__AAPL__leading_edge_soc dir `+` stress 9.1217

## §5 — RESOLUTIONS (since last pulse)

_no resolutions since the last pulse._

## §6 — CHECKPOINT OUTCOMES (since last pulse)

_Raw comparisons against the frozen reference. A comparison, **not a grade** — claims are graded only at resolution._

_no checkpoint passed since the last pulse._

---
_Tiers are stated: §1 is graded; §2/§3 are ungraded. Internal machinery (checkup evidence, amendment queue, stress-ledger internals, judge/repair rationales) never ships. Map changes reach buyers as epoch-boundary changelogs._
