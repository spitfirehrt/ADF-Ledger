# ADF PULSE — 2026-09-03

- epoch: v1  ·  run (UTC): `2026-09-03T05:25:31Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **9 open sealed claim(s)** (8 ALPHA / 1 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 0 proposed  ·  0 resolved since last pulse  ·  9 assessed (1 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260727T075315Z-C8` | CONSENSUS-HOLDS · graded (shadow-rate) | TSM · TSM__NVDA__leading_edge_wafers,TSM__AVGO__foundry_wafers,TSM__AMD__leading_edge_wafers | TSM September-2026 monthly revenue print, YoY  [>= +40%] | [1] | evidence-accumulating | 12 | Taiwan monthly print ~2026-09-10 | rising · 91% |
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 58 | Taiwan monthly print ~2026-09-10 | quiet · 27% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 58 | MU pre-announcement window ~2026-09-10 | falling · 6% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 58 | Taiwan monthly print ~2026-09-10 | falling · 27% |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 73 | Samsung Q3 preliminary guidance ~2026-10-08 | quiet · 30% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 73 | Taiwan monthly print ~2026-09-10 | rising · 76% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 88 | Taiwan monthly print ~2026-09-10 | quiet · 30% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 119 | MU pre-announcement window ~2026-09-10 | rising · 23% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 150 | Taiwan monthly print ~2026-09-10 | falling · 24% |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260727T075315Z-C8` — **rising · 91%** (+1 pts vs last pulse, from 90%)
  - case: TSMC 58% profit jump, +$100B Arizona add and Broadcom’s 30GW/$350B custom-AI calendar through FY28 all travel TSM__AVGO__foundry_wafers and TSM__NVDA__leading_edge_wafers, sustaining the ≥40% Sept monthly YoY anchor.
  - consensus: Street already bakes ~46–47% 0q revenue growth and strong_buy on TSM.
  - deviation: STRENGTHENING — incremental AI wafer demand and US capacity dollars confirm rather than challenge the ≥40% print.
  - synthesis: Base case remains September YoY ≥40%; hold as the book’s calibration anchor.
  - confidence: Prior 90 edged up on the explicit profit beat plus Broadcom multi-year silicon calendar gated by TSM wafers.
  - evidence: `CBMiowFBVV95cUxQb1FnRTZQemhk`, `CBMimAFBVV95cUxPd3NDc3RxbTlK`, `CBMijwFBVV95cUxNMDJ6VkZmOGZq`, `CBMilgFBVV95cUxPRXJ0bDJ6OWhK`

- `jobA-20260726T115635Z-C11` — **quiet · 27%** (+1 pts vs last pulse, from 26%)
  - case: NVDA $3.5B MediaTek convertible-bond and NVLink Fusion partnership flood the tape but never name a TSM foundry lane or a September monthly revenue print; the sealed TSM–MEDIATEK edge remains unobserved.
  - consensus: Street holds MediaTek 0q revenue growth around +10% with a strong_buy rating.
  - deviation: UNCHANGED — the claimed TSM wiring and the ≥5% Sept YoY print are still untested by any tagged item.
  - synthesis: Do not act; treat the edge as unproven and wait for the October monthly print.
  - confidence: Prior 26 nudges only on the NVDA capital injection’s eventual revenue optionality; no print or foundry disclosure moves the needle.
  - evidence: `CBMiowFBVV95cUxNZ0RUdFlNbGFm`, `CBMigAJBVV95cUxOVWZhOHdHR0w0`, `CBMiowFBVV95cUxQb1FnRTZQemhk`

- `jobA-20260727T075315Z-C4` — **falling · 6%** (-2 pts vs last pulse, from 8%) **⚠ FLAGGED**
  - case: SK Hynix CEO and multiple outlets extend the memory shortage through 2030 and call capacity sold-out; that rising-tide signal travels MU__SKHYNIX__hbm_capacity and MU__NVDA__hbm against any commodity-DRAM margin undershoot to ≤55% GM.
  - consensus: Street treats MU as pure HBM-scarcity winner (+349% growth baked, strong_buy).
  - deviation: WEAKENING — shortage-extension items reinforce the scarcity-winner frame the claim tries to fade.
  - synthesis: Q4 GM ≤55% remains a low-probability tail; stand down.
  - confidence: Prior 8 trimmed further; no CXMT-share or commodity-ASP print appeared while shortage-through-2030 headlines intensified.
  - evidence: `CBMikgFBVV95cUxQMDlQTjhIbGhy`, `CBMitwFBVV95cUxNTVp6SG9CNTRG`, `CBMigAFBVV95cUxQcmdzWWR2SGFY`
  - ⚠ **alert** (low_confidence): confidence 6% <= 10%

- `jobA-20260729T064012Z-C6` — **falling · 27%** (-8 pts vs last pulse, from 35%)
  - case: Nvidia–Amkor $1.5B packaging deal plus TSMC–Amkor Arizona and AMD advanced-packaging work activate AMKR__TSM__adv_packaging_overflow as a live AI revenue stream, pushing YoY growth away from the ≤15% Apple-mix cap toward the ≥19.8% fail zone.
  - consensus: Street still carries modest ~3–20% AMKR growth with a buy rating, treating it as overflow optionality.
  - deviation: WEAKENING — concrete NVDA/TSM/AMD packaging dollars make the AI-principal frame stronger than the Apple-seasonal cap.
  - synthesis: Apple-mix cap thesis is under direct pressure; do not lean into ≤15% until segment mix disproves the $1.5B AI book.
  - confidence: Prior 35 cut on the named $1.5B NVDA packaging contract and Arizona TSMC co-location that dominate near-term growth optics.
  - evidence: `CBMikAFBVV95cUxPd1JTdVJ1WE1z`, `CBMiqwFBVV95cUxOQ1AwM2c4dEpw`, `CBMiqAFBVV95cUxOMmlzQTBfZHN5`, `CBMixgFBVV95cUxQczlRYklTVEZP`

- `QCOM-septq-rev-yoy-2026` — **quiet · 30%** (-1 pts vs last pulse, from 31%)
  - case: Qualcomm modem/SoC price hikes land on AAPL__QCOM__handset_modems and SAMSUNG__QCOM__handset_socs, but the same window’s NVDA $3.5B MediaTek AI bet is framed as a direct rival offset; net zero on the Sept-q YoY path.
  - consensus: Street frames QCOM as a structural decliner (0q growth ~-10%, no rating).
  - deviation: UNCHANGED — price-hike support and MediaTek-rival headwind cancel; deviation neither strengthens nor weakens.
  - synthesis: Stay sidelined into the print; no clean read on whether growth clears -6.68%.
  - confidence: Prior 31 essentially flat; hikes help the observable but the explicit ‘Qualcomm rival’ MediaTek deal caps any upgrade.
  - evidence: `CBMidEFVX3lxTE9qZDJBTVJiSUQ1`, `CBMi1gFBVV95cUxQQnRmenBtYzJx`, `CBMiiAJBVV95cUxQZkFCQmdIb19y`

- `jobA-20260729T064012Z-C5` — **rising · 76%** (+2 pts vs last pulse, from 74%)
  - case: TSMC +$100B Arizona, tool-need nearly doubled and ‘equipment demand surged 90%’ items flow straight down TSM__KLA__process_control into KLA’s Sept-q revenue path toward ≥15% YoY.
  - consensus: Street gives KLA the weakest equipment-group rating (buy) and only ~13–26% growth.
  - deviation: STRENGTHENING — TSM capex intensity and process-control winner pieces widen the under-pricing gap the claim targets.
  - synthesis: Sept-q ≥15% remains base case; the relative-rating gap is the alpha, not the growth print itself.
  - confidence: Prior 74 lifted on the concrete Arizona $100B and doubled tool-need items; export-control share-price noise is the only offset.
  - evidence: `CBMimAFBVV95cUxPd3NDc3RxbTlK`, `CBMimwFBVV95cUxPUFpDRWxsV1dh`, `CBMidkFVX3lxTFBlWFBnSUl5SVhP`, `CBMinwFBVV95cUxNNk5jMEZCRWJk`

- `jobA-20260726T115635Z-C4` — **quiet · 30%**
  - case: LRCX Oregon lab, NT$9.8B Taiwan injection and ASE LEAP/panel-level packaging headlines run in parallel; no shipment, tool-of-record or design-win item links LRCX etch into ASX advanced packaging.
  - consensus: Street already prices LRCX ~+53% 0q revenue growth and a strong_buy.
  - deviation: UNCHANGED — the claimed LRCX→ASX supply edge and the ≥31% beat vs +29% consensus remain unwired.
  - synthesis: Observable stays at consensus until a shipment or design-win link appears; no action.
  - confidence: Prior 30 held; R&D and ASE demand items do not move LRCX.rev_yoy toward the sealed 31% threshold.

- `HBM-zerosum-skhynix-spread-2026` — **rising · 23%** (+12 pts vs last pulse, from 11%)
  - case: Samsung locks ~70% of HBM/memory output through 2031 and ships first HBM4E samples while Seoul Economic Daily flags ‘Samsung gains / SK hynix slides’; that allocation shift travels MU__SKHYNIX__hbm_capacity and SAMSUNG__NVDA__hbm toward SK underperformance on the sealed spread.
  - consensus: Street prices MU/SKHYNIX/SAMSUNG as a uniform HBM scarcity rally (all strong_buy, triple-digit growth).
  - deviation: STRENGTHENING — capacity-lock and rivalry-shift items make the zero-sum edge live rather than latent.
  - synthesis: Small relative underweight SKHYNIX vs SAMSUNG/MU is now evidence-supported into the Dec-2026 spread print.
  - confidence: Prior 11 lifted on the 70% lock and explicit Samsung-gains headline; still low because absolute shortage-through-2030 tide can keep all three rising together.
  - evidence: `CBMi1gFBVV95cUxQckdIRmtyUV9f`, `CBMingFBVV95cUxNNDI1b0hmaEEt`, `CBMikgFBVV95cUxQMDlQTjhIbGhy`

- `AVGO-wafer-hike-multiple-2027` — **falling · 24%** (-10 pts vs last pulse, from 34%)
  - case: Broadcom Q3 AI revenue $16.7B (+221%), FY27/FY28 guides $115B/$230B and 30GW/$350B custom-silicon calendar travel along TSM__AVGO__foundry_wafers as pure demand bid, overpowering any 2027 wafer-price cost shock on the multiple.
  - consensus: Street holds AVGO strong_buy, target ~526, 0q revenue growth ~94%.
  - deviation: WEAKENING — AI-demand narrative is being reinforced, not challenged, so the negative-sign hike thesis loses ground.
  - synthesis: Stand down the short-multiple; price path is being pulled toward the fail zone (≥560) not ≤480.
  - confidence: Prior 34 cut on the explicit FY27/FY28 double-and-double AI guides and 30GW backlog that dominate the cost-shock story.
  - evidence: `CBMilgFBVV95cUxPRXJ0bDJ6OWhK`, `CBMiXkFVX3lxTE5NY2FuVS1vUWts`, `CBMijwFBVV95cUxNMDJ6VkZmOGZq`, `CBMingFBVV95cUxNMHVNSmdqeHMy`

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
