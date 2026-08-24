# ADF PULSE — 2026-08-24

- epoch: v1  ·  run (UTC): `2026-08-24T05:59:41Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **9 open sealed claim(s)** (8 ALPHA / 1 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 0 proposed  ·  0 resolved since last pulse  ·  9 assessed (0 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260727T075315Z-C8` | CONSENSUS-HOLDS · graded (shadow-rate) | TSM · TSM__NVDA__leading_edge_wafers,TSM__AVGO__foundry_wafers,TSM__AMD__leading_edge_wafers | TSM September-2026 monthly revenue print, YoY  [>= +40%] | [1] | evidence-accumulating | 22 | Taiwan monthly print ~2026-09-10 | rising · 85% |
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 68 | Taiwan monthly print ~2026-09-10 | quiet · 26% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 68 | MU pre-announcement window ~2026-09-10 | falling · 13% |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 68 | Taiwan monthly print ~2026-09-10 | rising · 38% |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 83 | Samsung Q3 preliminary guidance ~2026-10-08 | falling · 42% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 83 | Taiwan monthly print ~2026-09-10 | rising · 70% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 98 | Taiwan monthly print ~2026-09-10 | quiet · 30% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 129 | MU pre-announcement window ~2026-09-10 | falling · 16% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 160 | Taiwan monthly print ~2026-09-10 | falling · 31% |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260727T075315Z-C8` — **rising · 85%** (+3 pts vs last pulse, from 82%)
  - case: TSMC sales +45% AI demand, Huang capacity lock via TSM__NVDA__leading_edge_wafers, AVGO $60B+ AI wafer pull via TSM__AVGO__foundry_wafers, and $85B/$100B capex all support sustained ≥40% monthly YoY into September.
  - consensus: Street already bakes ~+47% TSM growth (strong_buy; cited ~+46%).
  - deviation: STRENGTHENING — hard demand and capacity-lock items reinforce the calibration anchor rather than challenge it.
  - synthesis: Base case remains September YoY ≥40%; hold as the book’s calibration anchor.
  - confidence: Up from 82 on +45% sales print, NVDA capacity meeting, and AVGO AI financing all feeding leading-edge wafer demand edges.
  - evidence: `CBMifEFVX3lxTE9oWGx0TFRvc0Ji`, `CBMidkFVX3lxTFBuTTdZaWphdnQ3`, `CBMirAFBVV95cUxOelZnSUdLdjNC`, `CBMickFVX3lxTE9UME5mV1RnT1B1`

- `jobA-20260726T115635Z-C11` — **quiet · 26%**
  - case: Window is pure TSMC Arizona/$85B capex and AI-foundry demand; zero MediaTek revenue, design-win, or handset-SoC items touched the unwired TSM–MEDIATEK address.
  - consensus: Street holds MEDIATEK near-flat/slightly negative near-term growth (wall rev_growth_0q ~0.10; cited fail anchor -0.0245).
  - deviation: UNCHANGED — no MediaTek print or leading-edge allocation evidence moved the sealed September-2026 YoY observable.
  - synthesis: Do not act; treat the edge as unproven and wait for the October monthly print.
  - confidence: Unchanged from prior: still no MEDIATEK-tagged evidence and months remain to the Oct print.

- `jobA-20260727T075315Z-C4` — **falling · 13%** (-4 pts vs last pulse, from 17%)
  - case: Micron CEO scarcity/no-end-to-AI-memory, multi-year NVDA DRAM lock, and $10B Boise AI-memory campus all reinforce HBM/data-center tightness via MU__NVDA__hbm — opposite of commodity-DRAM/CXMT margin undershoot to ≤55% GM.
  - consensus: Street frames MU as pure HBM/AI scarcity winner (strong_buy, rev_growth ~+349%).
  - deviation: WEAKENING — every high-salience MU item this window deepens the scarcity-winner frame; no CXMT or commodity-ASP print.
  - synthesis: Q4 GM ≤55% remains a low-probability tail; stand down until a commodity-DRAM ASP or CXMT-share print appears.
  - confidence: Down from 17: CEO 50%+ shortage, multi-year NVDA deal, and $10B lab leave almost no room for the commodity-margin miss path near-term.
  - evidence: `CBMiqAFBVV95cUxNUElDTUk3YlNQ`, `CBMiyAFBVV95cUxNWDVrMlc4V0pz`, `CBMitAFBVV95cUxQcGthSVlVVm9U`, `CBMijwFBVV95cUxQYWFQRWtzV0ZQ`

- `jobA-20260729T064012Z-C6` — **rising · 38%** (+16 pts vs last pulse, from 22%)
  - case: Amkor shares crash after missing its own guidance directly supports the sealed ≤15% rev-growth observable and the Apple-mix cap via AAPL__AMKR__osat_packaging; CoWoS-overflow remains latent color only.
  - consensus: Street still carries a higher AMKR growth bar (cited ~+19.8%; wall now ~+2.9%) while AI-packaging narrative lingers.
  - deviation: STRENGTHENING — guidance miss/crash is hard evidence the Apple/seasonal book dominates over CoWoS-overflow upside.
  - synthesis: Miss-and-crash moves the ≤15% path into base case; lean into the claim on the next mix print rather than fade it.
  - confidence: Up hard from 22: guidance miss and share crash are the first direct negative AMKR operating prints toward the sealed ≤15% threshold.
  - evidence: `CBMiqAFBVV95cUxQMXItanFxQ185`, `CBMi5wFBVV95cUxNUEdBWHZ1ZW9i`, `CBMioAFBVV95cUxQNnlhMVN2Y2dQ`

- `QCOM-septq-rev-yoy-2026` — **falling · 42%** (-6 pts vs last pulse, from 48%)
  - case: Samsung Exynos 2700 internal-test outperformance vs Snapdragon travels SAMSUNG__QCOM__handset_socs against the sealed Samsung-flagship-SoC offset; Galaxy S27 Snapdragon teases are only soft positives beside handset-risk/QCOM-down-30% framing.
  - consensus: Street holds QCOM as structural handset decliner (hold, rev_growth_0q ~-10%).
  - deviation: WEAKENING — Exynos-beats-Snapdragon items cut the Samsung SoC win leg that was supposed to offset Apple modem risk.
  - synthesis: Stay sidelined into the print; Exynos headlines hurt the Samsung-offset case more than S27 teases help.
  - confidence: Down from 48 on Exynos-outperforms-Snapdragon evidence along SAMSUNG__QCOM__handset_socs; S27 teases only partially offset.
  - evidence: `CBMiV0FVX3lxTE5WN19yd1dyRTlO`, `CBMidkFVX3lxTFBKWGtCeWFnTW14`, `CBMivwFBVV95cUxNRVA3N0VleTlW`, `CBMipwFBVV95cUxOaWd2XzdzSWdY`

- `jobA-20260729T064012Z-C5` — **rising · 70%** (+4 pts vs last pulse, from 66%)
  - case: TSMC $85B spending forecast and +$100B Arizona capex travel TSM__KLA__process_control into KLA WFE; mild KLA guidance-digest selloffs do not cancel the customer-capex tailwind into the Sept quarter.
  - consensus: Street rates KLA only buy with the weakest equipment upside (wall rev_growth ~26%; cited ~13.5%).
  - deviation: STRENGTHENING — incremental TSM capex magnitude raises odds Sept-q clears the ≥15% bar via the sealed concentration edge.
  - synthesis: Sept-q ≥15% remains base case; the relative-rating gap is the alpha, not the growth print itself.
  - confidence: Up from 66 on repeated $85B TSM spend / $100B Arizona items tagged to TSM__KLA__process_control; KLA guidance noise is secondary.
  - evidence: `CBMimwFBVV95cUxNblllTmZ4OGNX`, `CBMickFVX3lxTE9UME5mV1RnT1B1`, `CBMilgFBVV95cUxPTXp3MTRKUWlZ`, `CBMic0FVX3lxTE40SklPd245ZXE1`

- `jobA-20260726T115635Z-C4` — **quiet · 30%**
  - case: LRCX posts AI-guidance/R&D-lab headlines and ASX buys machinery/LEAP mix, but nothing names an LRCX tool shipment or design-win into ASE advanced packaging.
  - consensus: Street already prices LRCX strong AI WFE growth (~+53% wall; cited ~+29% beat bar).
  - deviation: UNCHANGED — parallel bullishness at LRCX and ASX does not create the missing supply edge or move LRCX YoY through 31%.
  - synthesis: Observable stays at consensus until a shipment or design-win link appears; no action.
  - confidence: Unchanged: still no LRCX–ASX mechanism evidence; resolution not until late Nov.

- `HBM-zerosum-skhynix-spread-2026` — **falling · 16%** (-4 pts vs last pulse, from 20%)
  - case: NVIDIA multi-year DRAM locks with both SK hynix and Micron, shortage-to-2028, and NVDA server price hikes via SKHYNIX__NVDA__hbm / MU__NVDA__hbm / MU__SKHYNIX__hbm_capacity read as a rising tide, not SKH relative underperformance; Samsung HBM4 80% yield is competitive noise inside the same scarcity.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as uniform HBM/AI memory winners (all strong_buy, triple-digit growth).
  - deviation: WEAKENING — dual multi-year NVDA locks and shared shortage narrative undercut the zero-sum spread thesis.
  - synthesis: Do not fade SKHYNIX on the spread; scarcity is still a rising tide until an allocation or qualification share print appears.
  - confidence: Down from 20: multi-year SKH+MU NVDA deals and shortage-to-2028 directly oppose SKH lagging the MU/SAMSUNG mean.
  - evidence: `CBMiyAFBVV95cUxNWDVrMlc4V0pz`, `CBMidEFVX3lxTE5WUFhlYTdiYXJv`, `CBMiowFBVV95cUxNWDNuX1ViYm1a`, `CBMid0FVX3lxTE1wYWxsX3E3MHZP`

- `AVGO-wafer-hike-multiple-2027` — **falling · 31%** (-3 pts vs last pulse, from 34%)
  - case: AVGO $60–100B AI-debt/SPV headlines along TSM__AVGO__foundry_wafers plus TSMC capacity lock-in read as demand/multiple support, not a 2027 wafer-cost shock; no explicit 2027 wafer-price commentary.
  - consensus: Street is strong_buy AVGO on AI custom silicon (price ~368, target ~526).
  - deviation: WEAKENING — financing-led AI buildout narrative dominates; cost-shock leg of the claim got no new corroboration.
  - synthesis: Price is still under 480, but size down the short-multiple until an explicit 2027 wafer hike lands; AI-debt bid fights the thesis.
  - confidence: Down slightly from 34: AVGO mega-financing and TSM AI capacity news push the multiple the wrong way; still helped by spot price <<480 and long dated resolution.
  - evidence: `CBMirAFBVV95cUxOelZnSUdLdjNC`, `CBMixwFBVV95cUxOanUxeE1XaXZn`, `CBMickFVX3lxTFBYQlREdWpLaUdt`, `CBMifEFVX3lxTE9oWGx0TFRvc0Ji`

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
