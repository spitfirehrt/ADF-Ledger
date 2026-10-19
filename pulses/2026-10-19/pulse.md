# ADF PULSE — 2026-10-19

- epoch: v1  ·  run (UTC): `2026-10-19T09:54:10Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 1 active / 2 proposed  ·  0 resolved since last pulse  ·  8 assessed (3 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 12 | — | quiet · 56% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 12 | SK hynix Q3 earnings ~2026-10-24 | quiet · 1% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 12 | — | quiet · 2% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 27 | QCOM fiscal-Q4 FY26 earnings ~2026-11-05 | falling · 58% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 27 | Taiwan monthly print ~2026-11-10 | quiet · 84% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 42 | LRCX Sept-quarter earnings ~2026-10-22 | quiet · 28% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 73 | SK hynix Q3 earnings ~2026-10-24 | rising · 67% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 104 | Taiwan monthly print ~2026-11-10 | quiet · 3% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **quiet · 56%**
  - case: No MediaTek September-2026 monthly YoY print appears; ByteDance custom-AI talks are forward demand and do not move the sealed Sept print.
  - consensus: Street has MEDIATEK at strong_buy with 0q revenue growth ~0.12 and still frames it inside handset.
  - deviation: UNCHANGED — no Sept monthly actual landed to test the >=5% deviation vs the -2.45% cited wall.
  - synthesis: Stand by for the Taiwan monthly print; do not act on ByteDance headlines for this observable.
  - confidence: Unchanged: still no sealed-window actual; forward AI design-win noise does not raise or lower the Sept YoY probability.

- `jobA-20260727T075315Z-C4` — **quiet · 1%** **⚠ FLAGGED**
  - case: Prior pulse already retired the GM≤55% short; this window's MU-NVDA multi-year/HBM items only reconfirm the scarcity narrative that beat the claim.
  - consensus: MU strong_buy with extreme 0q growth (~350%) priced as pure HBM winner.
  - deviation: UNCHANGED — claim already failed; bullish HBM tape adds nothing new to a resolved observable.
  - synthesis: Stay flat; GM short is dead and evidence keeps the HBM-winner frame intact.
  - confidence: Floor held: observable resolved against the claim last pulse; no reverse print this window.
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `jobA-20260729T064012Z-C6` — **quiet · 2%** **⚠ FLAGGED**
  - case: Gwangju $2.3B AI-packaging capex and TSMC overflow commentary push the CoWoS-overflow frame along AMKR__TSM__adv_packaging_overflow; nothing pulls quarterly YoY back under 15%.
  - consensus: AMKR framed as AI packaging beneficiary; cited wall 0q growth ~19.8%.
  - deviation: UNCHANGED — AI-plant headlines reinforce the overflow narrative the claim bets against; Apple iPhone Duo is neutral mix.
  - synthesis: Do not lean ≤15%; trajectory already failed the short and this window adds AI capacity, not Apple-cap evidence.
  - confidence: Floor held: prior already above fail threshold; Gwangju AI spend moves the wrong way for the Apple-cap thesis.
  - evidence: `CBMidkFVX3lxTE8xMVJYSlJXMGxo`, `CBMi7gFBVV95cUxOdEJaLXBOUkZx`
  - ⚠ **alert** (low_confidence): confidence 2% <= 10%

- `QCOM-septq-rev-yoy-2026` — **falling · 58%** (-10 pts vs last pulse, from 68%)
  - case: Multiple S27 reports that Samsung may ditch Snapdragon on overheating/test fails hit SAMSUNG__QCOM__handset_socs and undercut the sealed 'new Samsung flagship SoC win' offset; Apple license renewal on AAPL__QCOM__handset_modems is only partial counterweight and does not restore the Sept-Q path.
  - consensus: QCOM hold, 0q rev growth ~-10%, framed as structural Apple-modem decliner.
  - deviation: WEAKENING — the claimed Samsung SoC offset is being actively reversed in test-fail coverage while the Apple renewal only stabilizes modems.
  - synthesis: Trim conviction on >-6.7% Sept-Q beat; Samsung flagship upside that justified the long is now at risk.
  - confidence: Down from 68: S27 ditch cluster directly attacks the claim's Samsung-win mechanism; Apple renew helps but cannot replace lost SoC content for the thesis, and print still unreleased.
  - evidence: `CBMiiwFBVV95cUxQN21TOXp3Ny1L`, `CBMiswFBVV95cUxQV0xUTkJKbW9C`, `CBMiyAFBVV95cUxOTTF5R0F6YkFv`, `CBMijwFBVV95cUxOcjdYekJkS0hZ`

- `jobA-20260729T064012Z-C5` — **quiet · 84%** (-3 pts vs last pulse, from 87%)
  - case: TSMC 69% profit, 44% 2026 sales raise and $98B capex-to-2028 support TSM__KLA__process_control, but 'capex unchanged' and equipment-stock losing-streak items add no new Sept-Q YoY actual.
  - consensus: KLA buy with weakest equipment-group rating/upside despite TSMC concentration; wall 0q growth ~0.13-0.26.
  - deviation: UNCHANGED — TSMC spend tailwind intact but unchanged-capex line and MS target cut prevent strengthening.
  - synthesis: Hold the Sept-Q ≥15% long as base case; no fresh confirmation or break.
  - confidence: Slightly down from 87 on TSMC 'capex unchanged' and toolmaker drawdown headlines; N2/3nm profit mix still anchors the ≥15% bar.
  - evidence: `CBMiV0FVX3lxTE5RUDJscC1VQXln`, `CBMitwFBVV95cUxOeGhNMWwzZC1h`, `CBMirgFBVV95cUxNbzRLdnlBeTBp`, `CBMiiAFBVV95cUxOWjFWdjU5aTZ1`

- `jobA-20260726T115635Z-C4` — **quiet · 28%**
  - case: ASX 44.8% rev growth and capacity expansion plus LRCX drawdown on AI-spend fears still carry no LRCX-ASX tool-supply disclosure that would move LRCX YoY rev.
  - consensus: LRCX is strong_buy with ~53% 0q growth priced; ASX strong_buy on AI packaging.
  - deviation: UNCHANGED — no mechanism linking LRCX tools into ASX advanced packaging was evidenced.
  - synthesis: Remain stood down until a direct LRCX-to-ASX equipment disclosure; observable untested.
  - confidence: Unchanged: ASX strength and LRCX stock weakness are orthogonal to the missing supply-edge proof and the 31% YoY bar.

- `HBM-zerosum-skhynix-spread-2026` — **rising · 67%** (+5 pts vs last pulse, from 62%)
  - case: Samsung/TSMC/Nvidia custom-HBM base-die co-design elevates SAMSUNG__NVDA__hbm while Micron multi-year NVDA deals lift MU; SK hynix HBM4-delay ADR weakness travels MU__SKHYNIX__hbm_capacity toward SKHYNIX underperformance vs peers.
  - consensus: Memory cluster priced as uniform melt-up (MU/SKHYNIX/SAMSUNG all strong_buy, triple-digit growth).
  - deviation: STRENGTHENING — Samsung catch-up via TSMC 3nm base die plus MU NVDA tie-ups and SKH HBM4 delay re-open zero-sum share risk the wall ignores.
  - synthesis: Lean the <=-10% SKHYNIX-vs-MU/SAMSUNG spread; relative losers are now visible on the board edges.
  - confidence: Up from 62 on Samsung custom-HBM qualification path and SKH delay item; still two months to Dec-31 and all-three TSMC-base-die unity caps how hard the zero-sum bites.
  - evidence: `CBMi6AFBVV95cUxNdWc0aFpWb0cx`, `CBMi0AFBVV95cUxQLVd3RU5QdzNw`, `CBMingFBVV95cUxQNktLNkVySGN2`, `CBMidkFVX3lxTE5GYURYMGp2WFVY`, `CBMiqgFBVV95cUxQT3g3ei1WVGVD`

- `AVGO-wafer-hike-multiple-2027` — **quiet · 3%** **⚠ FLAGGED**
  - case: CNBC fierce TSMC-capacity battle naming Broadcom and TSMC record AI profit reinforce demand pull along TSM__AVGO__foundry_wafers; no 2027 wafer-hike or margin-compression print.
  - consensus: AVGO strong_buy, target ~528, 0q growth ~94% — AI demand strictly positive.
  - deviation: UNCHANGED — capacity scramble is read as volume tailwind, not as the sealed negative cost shock.
  - synthesis: Keep ≤480 Jan-2027 short stood down; path of least resistance still higher on allocation scarcity.
  - confidence: Unchanged at floor: spot ~329 already under 480 but resolution is Jan-2027 and every item this window supports multiple expansion, not compression.
  - evidence: `CBMipgFBVV95cUxOM1JWVlV1cHBx`, `CBMingFBVV95cUxPcTFFbGhXV2lU`, `CBMiygFBVV95cUxPX0JVdlhVemVk`
  - ⚠ **alert** (low_confidence): confidence 3% <= 10%

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
- AAPL dir `+` stress 13.0552
- TSM__AAPL__leading_edge_soc dir `+` stress 8.8694

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
