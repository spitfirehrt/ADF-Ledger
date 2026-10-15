# ADF PULSE — 2026-10-15

- epoch: v1  ·  run (UTC): `2026-10-15T13:58:42Z`  ·  spec: docs/PULSE-PAYLOAD.md (Blueprint v1.14)
- **8 open sealed claim(s)** (8 ALPHA / 0 calibration)  ·  0 watch  ·  3 tracked  ·  shocks: 0 active / 0 proposed  ·  0 resolved since last pulse  ·  8 assessed (3 flagged)

## §1 — SEALED (the record; graded)

| id | tag · tier | address | observable | win | status | days→res | next checkpoint | pressure · confidence |
|---|---|---|---|:--:|---|--:|---|---|
| `jobA-20260726T115635Z-C11` | ALPHA · graded (ALPHA confirm-rate) | TSM,MEDIATEK | MediaTek September-2026 monthly revenue print, YoY  [>= +5%] | [1] | evidence-accumulating | 16 | — | quiet · 56% |
| `jobA-20260727T075315Z-C4` | ALPHA · graded (ALPHA confirm-rate) | MU · MU__SKHYNIX__hbm_capacity | MU GAAP consolidated gross margin, fiscal Q4 FY2026 (earnings release, ~late Sept 2026)  [<= 55%] | [1] | evidence-accumulating | 16 | SK hynix Q3 earnings ~2026-10-24 | quiet · 1% **!** |
| `jobA-20260729T064012Z-C6` | ALPHA · graded (ALPHA confirm-rate) | AMKR · AAPL__AMKR__osat_packaging,AMKR__TSM__adv_packaging_overflow | AMKR quarterly revenue YoY growth  [<= +15%] | [1] | evidence-accumulating | 16 | — | quiet · 2% **!** |
| `QCOM-septq-rev-yoy-2026` | ALPHA · graded (ALPHA confirm-rate) | QCOM · SAMSUNG__QCOM__handset_socs,AAPL__QCOM__handset_modems | QCOM FY2026 Sept-quarter (fiscal Q4) revenue YoY growth  [> -6.68%] | [1] | evidence-accumulating | 31 | QCOM fiscal-Q4 FY26 earnings ~2026-11-05 | quiet · 68% |
| `jobA-20260729T064012Z-C5` | ALPHA · graded (ALPHA confirm-rate) | KLA · TSM__KLA__process_control | KLA September-2026 quarter revenue YoY growth (FY2027 Q1, quarter ending 2026-09-30)  [>= +15%] | [1] | evidence-accumulating | 31 | Taiwan monthly print ~2026-11-10 | quiet · 87% |
| `jobA-20260726T115635Z-C4` | ALPHA · graded (ALPHA confirm-rate) | LRCX,ASX | LRCX latest-quarter revenue YoY growth (beats the cited +29% consensus)  [>= +31%] | [1] | evidence-accumulating | 46 | LRCX Sept-quarter earnings ~2026-10-22 | quiet · 28% |
| `HBM-zerosum-skhynix-spread-2026` | ALPHA · graded (ALPHA confirm-rate) | MU,SKHYNIX,SAMSUNG · MU__SKHYNIX__hbm_capacity,SKHYNIX__NVDA__hbm,SAMSUNG__NVDA__hbm | SKHYNIX total return minus mean total return of {MU, SAMSUNG}, seal date to 2026-12-31  [<= -10%] | [2] | evidence-accumulating | 77 | SK hynix Q3 earnings ~2026-10-24 | quiet · 62% |
| `AVGO-wafer-hike-multiple-2027` | ALPHA · graded (ALPHA confirm-rate) | AVGO,TSM · TSM__AVGO__foundry_wafers | AVGO share price (multiple/margin compression)  [<= $480] | [2] | evidence-accumulating | 108 | Taiwan monthly print ~2026-11-10 | quiet · 3% **!** |

_The `pressure · confidence` column is a **machine assessment — the sealed claim is unchanged**. Confidence is the machine's probability the claim confirms at resolution; it is **not graded** and moves no rate. `!` marks a flagged reading (see the per-claim lines below)._

**machine assessment — per claim** _(the sealed rows above are unchanged)_

- `jobA-20260726T115635Z-C11` — **quiet · 56%**
  - case: No tagged items landed on TSM or MEDIATEK this window; MediaTek September-2026 monthly revenue print remains unreleased and unmoved.
  - consensus: Street holds MEDIATEK 0q revenue growth near -0.0245 with strong_buy framing.
  - deviation: UNCHANGED — no print or telemetry arrived to test the >=5% YoY deviation.
  - synthesis: Stand by for the ~Oct 10 MediaTek Taiwan monthly; nothing in this window moves the claim.
  - confidence: Unchanged from prior; still pre-print with no new information to raise or lower odds.

- `jobA-20260727T075315Z-C4` — **quiet · 1%** **⚠ FLAGGED**
  - case: No tagged items on MU; prior resolution already showed GM observable against the <=55% claim and nothing new arrived.
  - consensus: Street treats MU as HBM-scarcity winner with extreme 0q growth (~3.5x) and strong_buy.
  - deviation: UNCHANGED — claim already failed on the sealed GM print; this window adds no further data.
  - synthesis: GM≤55% short fully retired; observable has resolved against the claim.
  - confidence: Remains near-zero; no path left for confirmation after prior adverse resolution.
  - ⚠ **alert** (low_confidence): confidence 1% <= 10%

- `jobA-20260729T064012Z-C6` — **quiet · 2%** **⚠ FLAGGED**
  - case: No tagged items on AMKR or the AAPL/TSM packaging edges; quarterly YoY growth observable unmoved.
  - consensus: Street implies AMKR 0q growth ~0.20 with no formal rating and AI-packaging upside narrative.
  - deviation: UNCHANGED — no print to push growth back under 15% or confirm the Apple-mix cap.
  - synthesis: Do not lean ≤15%; prior trajectory already sits above the fail threshold and nothing reversed it.
  - confidence: Stays minimal; claim remains on the wrong side of its own fail line with empty window.
  - ⚠ **alert** (low_confidence): confidence 2% <= 10%

- `QCOM-septq-rev-yoy-2026` — **quiet · 68%**
  - case: No tagged items on QCOM or the Samsung/Apple handset edges; FYQ4 revenue print still pending and unmoved.
  - consensus: Street frames QCOM as hold with 0q revenue growth ~-0.10.
  - deviation: UNCHANGED — no actual or pre-announcement to push YoY above or below the -6.7% line.
  - synthesis: Hold the >-6.7% long into Nov FYQ4; still waiting on the actual print.
  - confidence: Flat; calendar closer but zero evidence arrived to adjust probability.

- `jobA-20260729T064012Z-C5` — **quiet · 87%**
  - case: No tagged items on KLA or TSM__KLA__process_control; September-quarter YoY growth print still outstanding.
  - consensus: Street gives KLA the weakest equipment-group rating (buy) and ~0.13–0.26 growth vs peers’ stronger buys.
  - deviation: UNCHANGED — no revenue or TSM-capex telemetry to strengthen or weaken the >=15% case.
  - synthesis: Sept-q ≥15% remains base case; hold the long with no new support or contradiction.
  - confidence: Unchanged; high prior base intact because nothing adverse appeared and threshold is modest vs wall.

- `jobA-20260726T115635Z-C4` — **quiet · 28%**
  - case: No tagged items on LRCX or ASX; no tool-disclosure or revenue print to test the advanced-packaging supply edge or the >=31% YoY observable.
  - consensus: Street prices LRCX 0q revenue growth ~0.29 with strong_buy.
  - deviation: UNCHANGED — observable still untested and no LRCX-ASX linkage evidence appeared.
  - synthesis: Remain stood down until a direct LRCX-ASX tool disclosure; observable still untested.
  - confidence: Flat vs prior; absence of any equipment or OSAT telemetry leaves the low base intact.

- `HBM-zerosum-skhynix-spread-2026` — **quiet · 62%**
  - case: No tagged items on MU, SKHYNIX, SAMSUNG or the HBM edges; zero-sum spread observable unmoved this window.
  - consensus: Street prices memory cluster uniformly strong_buy with elevated targets across MU/SKHYNIX/SAMSUNG.
  - deviation: UNCHANGED — no HBM allocation or share-shift evidence to tighten or loosen the spread case.
  - synthesis: Lean the <=-10% SKHYNIX-vs-peers spread short still live on mechanism, but nothing new this pulse.
  - confidence: Held at prior; no telemetry to confirm Samsung share grab or reverse it.

- `AVGO-wafer-hike-multiple-2027` — **quiet · 3%** **⚠ FLAGGED**
  - case: No tagged items on AVGO or TSM; AVGO price sits well above the <=480 threshold with no wafer-hike margin signal this window.
  - consensus: Street holds AVGO strong_buy with mean target ~528 and high teens-to-90%+ growth framing.
  - deviation: UNCHANGED — no price or cost-shock evidence moved the multiple toward compression.
  - synthesis: Keep ≤480 short-multiple stood down; path of least resistance still higher into Jan-2027.
  - confidence: Unchanged; still far from threshold with long calendar and zero fresh negative pressure.
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

**board quiet — zero shocks.** The map sees no structural change; recent moves read as flow, not dependency stress.

## §5 — RESOLUTIONS (since last pulse)

_no resolutions since the last pulse._

## §6 — CHECKPOINT OUTCOMES (since last pulse)

_Raw comparisons against the frozen reference. A comparison, **not a grade** — claims are graded only at resolution._

_no checkpoint passed since the last pulse._

---
_Tiers are stated: §1 is graded; §2/§3 are ungraded. Internal machinery (checkup evidence, amendment queue, stress-ledger internals, judge/repair rationales) never ships. Map changes reach buyers as epoch-boundary changelogs._
