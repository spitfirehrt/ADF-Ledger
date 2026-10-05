# ADF PULSE — 2026-10-05

- epoch: v1  ·  run (UTC): `2026-10-05T09:02:44Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 0 proposed  ·  0 resolved since last pulse  ·  8 assessed (3 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 26 | Taiwan monthly print ~2026-10-10 | quiet · 56% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 26 | SK hynix Q3 earnings ~2026-10-24 | falling · 1% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 26 | Taiwan monthly print ~2026-10-10 | falling · 2% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 41 | Samsung Q3 preliminary guidance ~2026-10-08 | rising · 72% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 41 | Taiwan monthly print ~2026-10-10 | rising · 90% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 56 | Taiwan monthly print ~2026-10-10 | quiet · 28% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 87 | Samsung Q3 preliminary guidance ~2026-10-08 | rising · 48% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 118 | Taiwan monthly print ~2026-10-10 | falling · 4% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **quiet · 56%**
  - case: No September-2026 MediaTek monthly revenue print yet; only a Dimensity 9600 Pro launch item, which does not move the YoY revenue observable.
  - consensus: Street holds MediaTek 0q revenue growth near -2.45% with a strong_buy rating and no wired TSM foundry edge.
  - deviation: UNCHANGED — product launch does not alter the sealed monthly-revenue deviation test.
  - synthesis: Stand by for the ~Oct 10 MediaTek Taiwan monthly; nothing in this window moves the claim.
  - confidence: Unchanged from prior; still waiting on the actual September print with no new information.

- `jobA-20260727T075315Z-C4` — **falling · 1%** **⚠ FLAGGED**
  - case: MU 88% consumer-memory margin, blowout earnings, and CEO sold-out/shortage-through-2028 commentary confirm consolidated GM far above the ≤0.55 short threshold.
  - consensus: Street already prices MU as HBM-scarcity winner with +350% growth and strong_buy.
  - deviation: WEAKENING — margin and backlog prints have already resolved against the undershoot claim.
  - synthesis: GM≤55% short fully retired; observable has resolved against the claim.
  - confidence: Held at prior 1; 88% margin item leaves no path to ≤55% confirmation.
  - evidence: `CBMiqwJBVV95cUxOV0YwTmVqQkdl`, `CBMilgFBVV95cUxPTERLUlNXYXNn`, `CBMivgFBVV95cUxPOEpNSWZVSnM1`
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 2%** **⚠ FLAGGED**
  - case: AMKR AI/HPC packaging demand and 'AI packaging story' items keep the CoWoS-overflow narrative dominant; no Apple-mix deceleration evidence to pull YoY ≤15%.
  - consensus: Street still frames AMKR around AI packaging upside (target 76 vs 56) despite low printed 0q growth.
  - deviation: WEAKENING — AI-packaging headlines continue to dominate the Apple-seasonality cap the claim needs.
  - synthesis: Do not lean ≤15%; AI narrative and prior prints already sit above the fail threshold.
  - confidence: Held at prior 2; fresh AI/HPC demand items leave no path back under 15%.
  - evidence: `CBMiuAFBVV95cUxPWm9PT19YWFZI`, `CBMiqwFBVV95cUxPd1VXb1hGUDlN`
  - ⚠ **alert** (low_confidence): confidence 2% <= 10%

- `QCOM-septq-rev-yoy-2026` — **rising · 72%** (+4 pts vs last pulse, from 68%)
  - case: Apple modem/patent deal extension into 2027 directly supports AAPL__QCOM__handset_modems revenue continuity, offsetting the structural-decliner frame into the Sept FYQ4 print.
  - consensus: Street holds QCOM as hold with 0q rev growth ~-10%, framed as Apple-insourcing structural decliner.
  - deviation: STRENGTHENING — multi-year Apple extension is concrete positive vs the -6.7% deviation threshold.
  - synthesis: Hold the >-6.7% long into Nov FYQ4; Apple extension is the live offset.
  - confidence: Prior 68 raised on the explicit 2027 Apple extension; Huawei patent is secondary support, Samsung SoC leg still thin.
  - evidence: `CBMixwFBVV95cUxPUmxndENkcHJf`, `CBMijwFBVV95cUxPTElCQmVJTW9f`, `CBMiswFBVV95cUxQc1Fib0QzOFI0`

- `jobA-20260729T064012Z-C5` — **rising · 90%** (-1 pts vs last pulse, from 91%)
  - case: TSMC $265B US-expansion item explicitly tags TSM__KLA__process_control; Nvidia-quarter 'hidden partner KLA' note adds incremental N2/AI process-control demand into the Sept-q ≥15% test.
  - consensus: Street gives KLA the weakest equipment-group rating (buy) and only ~13-26% growth vs peers' strong_buys.
  - deviation: STRENGTHENING — TSM capex and NVDA-linked process-control callouts support the under-priced concentration thesis.
  - synthesis: Sept-q ≥15% remains base case with incremental TSM-capex support; hold the long.
  - confidence: Prior 91 held; TSM expansion and NVDA-KLA items offset the Zacks Hold downgrade noise.
  - evidence: `CBMiqgFBVV95cUxOT1ZLN29MTHIy`, `CBMif0FVX3lxTFBMcDE2bmZEb2Ru`

- `jobA-20260726T115635Z-C4` — **quiet · 28%**
  - case: ASX CoWoS/panel and capex items plus LRCX facility/Micron-backlog notes remain separate; no disclosure tying LRCX tools into ASX advanced packaging.
  - consensus: Street prices LRCX at +29% 0q growth / strong_buy and ASX on packaging overflow, with no LRCX→ASX equipment edge.
  - deviation: UNCHANGED — no direct LRCX-ASX tool or revenue-link evidence appeared.
  - synthesis: Remain stood down until a direct LRCX-ASX tool disclosure; observable still untested.
  - confidence: Flat vs prior; still no mechanism evidence and resolution is weeks away.

- `HBM-zerosum-skhynix-spread-2026` — **rising · 48%** (+6 pts vs last pulse, from 42%)
  - case: MU CEO shortage-through-2028, 75% 2027 sold-out, $32B backlog and 88% consumer-memory margin items travel MU__SKHYNIX__hbm_capacity as share/pricing grab vs SKHYNIX; Samsung HBM4 3x pricing is parallel not offsetting.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as uniform HBM rally (all strong_buy, triple-digit growth).
  - deviation: STRENGTHENING — MU share-grab and sold-out commentary make the zero-sum edge live against SKHYNIX relative performance.
  - synthesis: Lean the Dec SKHYNIX-vs-peers spread short; MU share grab remains the live mechanism.
  - confidence: Prior 42 lifted on MU backlog/sold-out and margin specifics that tighten the relative underperformance path for SKHYNIX.
  - evidence: `CBMiuAFBVV95cUxNOTN3WXdfcDkz`, `CBMilgFBVV95cUxPTERLUlNXYXNn`, `CBMiWEFVX3lxTFB2VU8zRC15V2Ey`, `CBMiqwJBVV95cUxOV0YwTmVqQkdl`

- `AVGO-wafer-hike-multiple-2027` — **falling · 4%** (-1 pts vs last pulse, from 5%) **⚠ FLAGGED**
  - case: AVGO AI guide to $21.7B, Q3 AI +221%, and $42-60B Anthropic financing/underwriting packages all lift the multiple along TSM__AVGO__foundry_wafers, pushing price away from ≤480.
  - consensus: Street has AVGO strong_buy, target ~531, treating AI demand as strictly positive for the multiple.
  - deviation: WEAKENING — financing and guide strength reinforce the positive-AI narrative the claim bets against.
  - synthesis: Keep ≤480 short-multiple stood down; path of least resistance still higher into Jan-2027.
  - confidence: Prior 5 cut slightly; fresh $60B/Anthropic and guide items further distance price from the short threshold.
  - evidence: `CBMioAFBVV95cUxOS3d0Uzc0bl9Y`, `CBMitAFBVV95cUxQcTlfRWNuNFBk`, `CBMirwFBVV95cUxQbzU3NnV4NFhN`
  - ⚠ **alert** (low_confidence): confidence 4% <= 10%

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
