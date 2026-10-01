# ADF PULSE — 2026-10-01

- epoch: v1  ·  run (UTC): `2026-10-01T05:16:51Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 1 proposed  ·  0 resolved since last pulse  ·  8 assessed (3 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 30 | Taiwan monthly print ~2026-10-10 | quiet · 56% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 30 | SK hynix Q3 earnings ~2026-10-24 | falling · 1% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 30 | Taiwan monthly print ~2026-10-10 | falling · 2% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 45 | Samsung Q3 preliminary guidance ~2026-10-08 | falling · 68% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 45 | Taiwan monthly print ~2026-10-10 | rising · 91% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 60 | Taiwan monthly print ~2026-10-10 | quiet · 28% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 91 | Samsung Q3 preliminary guidance ~2026-10-08 | rising · 42% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 122 | Taiwan monthly print ~2026-10-10 | falling · 5% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **quiet · 56%** (-2 pts vs last pulse, from 58%)
  - case: TSM 2nm scale-to-120k wpm and Chiayi packaging adds are ambient foundry-capacity positives with no MediaTek tag and no September monthly print; nothing moved MEDIATEK.revenue_growth toward or away from +5%.
  - consensus: Street holds MediaTek 0q revenue growth at -2.45% with no wired TSM edge.
  - deviation: UNCHANGED — capacity headlines do not touch the sealed monthly observable.
  - synthesis: Stand by for ~Oct 10 MediaTek monthly; no new information this window.
  - confidence: Prior 58 trimmed 2 pts; still no MediaTek-specific print and only indirect TSM capacity noise.

- `jobA-20260727T075315Z-C4` — **falling · 1%** (-1 pts vs last pulse, from 2%) **⚠ FLAGGED**
  - case: MU already printed Q4 FY2026 record $54.23B revenue and $37.7B GAAP profit with data-center revenue up 11-fold — the GM≤55% short is mechanically dead on the release the sealed window was waiting for.
  - consensus: Street treats MU as pure HBM-scarcity winner with 0q growth ~349%.
  - deviation: WEAKENING — print and guide confirm scarcity-margin expansion, opposite the commodity-DRAM undershoot thesis.
  - synthesis: GM≤55% short fully retired; observable has resolved against the claim.
  - confidence: Prior 2 cut to 1; Q4 release is the sealed actual_key source and is incompatible with ≤55% GM.
  - evidence: `CBMiswFBVV95cUxQUGpHRE1mMFNY`, `CBMiekFVX3lxTE1PSFA1cXl4cDVI`
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 2%** (-2 pts vs last pulse, from 4%) **⚠ FLAGGED**
  - case: TSMC five new Chiayi packaging plants reduce overflow via AMKR__TSM__adv_packaging_overflow while Amkor already prints +25.6% rev growth — both move the observable away from ≤15% and past the 19.82% fail line.
  - consensus: Street frames AMKR as CoWoS-overflow AI packaging with 0q growth ~20%.
  - deviation: WEAKENING — live +25.6% print and TSM internal packaging build both reject the Apple-capped ≤15% short.
  - synthesis: Do not lean ≤15%; observable already printing above fail threshold.
  - confidence: Prior 4 cut to 2 on explicit 25.6% AMKR growth print plus TSM packaging internalization.
  - evidence: `CBMiuAFBVV95cUxNOG82UF9KcVg1`, `CBMidkFVX3lxTFA4SVU4WGZpTVRG`, `CBMidEFVX3lxTE02blJvMHZucm0t`, `CBMi2gFBVV95cUxOLVEtZUdXS3ZP`
  - ⚠ **alert** (low_confidence): confidence 2% <= 10%

- `QCOM-septq-rev-yoy-2026` — **falling · 68%** (-17 pts vs last pulse, from 85%)
  - case: Stalled Samsung negotiations directly undercut the sealed SAMSUNG__QCOM__handset_socs offset, while Apple patent renewal through 2027 and 2027-modem-ditch headlines leave the Sept-2026 quarter only partially defended on AAPL__QCOM__handset_modems.
  - consensus: Street hold QCOM with 0q growth -10% framed as Apple-modem structural decline.
  - deviation: WEAKENING — Samsung stall removes the thesis's second pillar even as patent renewal holds the Apple floor.
  - synthesis: Trim long-QCOM conviction into Nov FYQ4; Samsung SoC-win leg is now impaired.
  - confidence: Prior 85 cut 17 pts on explicit Samsung negotiation stall; patent renewal still supports >-6.68% but with less margin of safety.
  - evidence: `CBMidkFVX3lxTFBjdDNHWVd0NGZk`, `CBMiogFBVV95cUxOd1VlU3Z2bWhW`, `CBMibkFVX3lxTFBZOXpwbmp6MDZZ`, `CBMinwFBVV95cUxQTklLd251TTRq`

- `jobA-20260729T064012Z-C5` — **rising · 91%** (+3 pts vs last pulse, from 88%)
  - case: TSMC Arizona six-fab/$165B and 2nm expansion plus KLAC backlog-surge / higher-revenue-bar guidance travel TSM__KLA__process_control as direct capex tailwind into the Sept-2026 quarter ≥15% print.
  - consensus: Street rates KLA only buy with the weakest equipment-group upside despite TSM concentration.
  - deviation: STRENGTHENING — backlog and TSM US/2nm spend headlines raise odds the sealed ≥15% clears.
  - synthesis: Sept-q ≥15% is now the base case with incremental TSM-capex support; hold the long.
  - confidence: Prior 88 raised 3 pts on explicit KLAC backlog surge and TSM Arizona/2nm WFE linkage.
  - evidence: `CBMiWEFVX3lxTE0xODUwaE9zT3lM`, `CBMitAFBVV95cUxNZlh3WTFVQ3M2`, `CBMisAFBVV95cUxQeW41WVg4T3Fu`, `CBMivAFBVV95cUxOeTJybUJVRURv`

- `jobA-20260726T115635Z-C4` — **quiet · 28%**
  - case: LRCX Livermore warehouse opens and ASX +34.6% rev / Singapore test-fab buy run on separate nodes; no LRCX-ASX tool PO or advanced-packaging equipment disclosure appears.
  - consensus: Street has LRCX 0q growth ~53% and ASX as CoWoS-overflow OSAT; no LRCX→ASX supply edge is modeled.
  - deviation: UNCHANGED — parallel positives do not evidence the missing edge.
  - synthesis: Remain stood down until a direct LRCX-ASX tool disclosure.
  - confidence: No reason to move off prior 28; still zero direct edge evidence.

- `HBM-zerosum-skhynix-spread-2026` — **rising · 42%** (+7 pts vs last pulse, from 35%)
  - case: MU Q4 $54.23B / Q1 guide $60-63B blowout and 11-fold data-center jump travel MU__SKHYNIX__hbm_capacity as share-gain pressure that widens SKHYNIX underperformance vs the MU leg of the sealed spread.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as uniform strong_buy HBM rally with no zero-sum haircut.
  - deviation: STRENGTHENING — MU print magnitude vs still-qualitative SKH HBM5/TSMC validation tilts the relative spread toward the sealed ≤-10% outcome.
  - synthesis: Lean the Dec SKHYNIX-vs-peers spread short; MU share grab is the live mechanism.
  - confidence: Prior 35 raised 7 pts on MU blowout size via the zero-sum edge; SKH HBM5-with-TSMC and Jensen dual-meetings still cap upside.
  - evidence: `CBMiqAFBVV95cUxPZzdZT0xCOTBp`, `CBMiekFVX3lxTE1PSFA1cXl4cDVI`, `CBMicEFVX3lxTE5wbzBPaGpZSy0z`, `CBMijwFBVV95cUxPNWdxNDRkWjI1`

- `AVGO-wafer-hike-multiple-2027` — **falling · 5%** **⚠ FLAGGED**
  - case: TSMC 2nm to 120k wpm, capacity sold out through 2028, and Apple/Nvidia demand boost travel TSM__AVGO__foundry_wafers as pure volume tailwind that absorbs any 2027 price hike into the AI-demand multiple.
  - consensus: Street strong_buy AVGO with mean target ~532 and 0q growth +94%.
  - deviation: WEAKENING — sold-out/2nm expansion headlines reinforce the demand-overrides-cost narrative against the ≤480 short.
  - synthesis: Keep ≤480 short-multiple stood down; path of least resistance still higher into Jan-2027.
  - confidence: Prior 5 held; incremental sold-out-through-2028 and 2nm scale add no path to sub-480 by resolution.
  - evidence: `CBMisAFBVV95cUxNQkVwa2dKWUtY`, `CBMixwFBVV95cUxQMmh5MFVXMWhE`, `CBMimgFBVV95cUxOTWtUWmY2OEtw`
  - ⚠ **alert** (low_confidence): confidence 5% <= 10%

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
- TSM__INTC__external_foundry dir `+` stress 1.6638

## §5 — RESOLUTIONS (since last pulse)

_no resolutions since the last pulse._

## §6 — CHECKPOINT OUTCOMES (since last pulse)

_Raw comparisons against the frozen reference. A comparison, **not a grade** — claims are graded only at resolution._

_no checkpoint passed since the last pulse._

---
_Tiers are stated: §1 is graded; §2/§3 are ungraded. Internal machinery (checkup evidence, amendment queue, stress-ledger internals, judge/repair rationales) never ships. Map changes reach buyers as epoch-boundary changelogs._
