# Prehistory Ledger — PLACEHOLDER (awaiting operator/architect text)

> **STATUS: placeholder.** The final prehistory-ledger text — the pre-launch
> record and its **curation line** (the explicit statement of what was and was
> not curated, so the record stays honest) — will be **handed over by the
> architect**. This file exists so the publish path has a stable target; replace
> its contents with the final text before the public launch. Do not point copy at
> it until it is filled in.

## What this file is (once written)

The prehistory ledger is the **one-time, pre-launch record** that sits alongside
the live sealed ledger: the account of what existed before the first sealed epoch,
presented with a curation line so a reader knows exactly how it was assembled and
what judgment went into it. It is **published once** into `adf-ledger` and then
left append-only like everything else here.

## What it must contain (to be supplied)

- The pre-launch narrative / record itself (architect-provided).
- A **curation line**: a plain statement of what was selected, what was left out,
  and on what basis — the honesty stamp that keeps a curated record trustworthy.
- Nothing private: no graph internals, weights, mechanisms, prompts, or reasoning
  (same boundary as the rest of the public ledger).

---

*Until this file is replaced with the final text, `tools/publish_ledger.py` will
still publish it (as a visible placeholder). That is intentional — a missing
prehistory file is worse than a labeled placeholder. Swap in the real text, then
re-run the publish.*
