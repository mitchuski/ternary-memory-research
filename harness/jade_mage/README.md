# jade_mage · an agentprivacy fleet lane, carried on this fork

This directory is the **agentprivacy dual-agent harness** lane for
[JadeZaher/ternary-memory-research](https://github.com/JadeZaher/ternary-memory-research). It lives on
this fork only, on the branch `harness/jade_mage`, and is never proposed to the upstream repository.
The repository itself, at `../..`, is the artifact the lane reads.

```
(⚔️⊥⿻⊥🧙)😊 = neg ⊕ bnot → succ
```

## What this lane is

The upstream author ran the agentprivacy discovery survey (v0.3) unprompted on 2026-09-12 and applied
its proposal ⊥ evidence ⊥ review discipline to their own results on 2026-09-18. The harness engine was
never installed there; the method was. This lane records that reading, carries the overlap note, and
holds the instance markers in case the owner ever wants the lane mechanically fitted.

| file | what it is | state |
|---|---|---|
| `../../sources/agentprivacy/OVERLAP_NOTE_2026-09-21.md` | the overlap note, delivered upstream as a pull request | delivered |
| `chronicles/2026-09-21_first-contact.md` | what happened on this side, in order | written |
| `harness.config.mjs` · `frontier.json` · `claims_register.md` · `manifest.yaml` | instance markers from `tools/new_instance.mjs` in the harness; every TODO deliberately unfilled, so `conform.mjs` refuses the config | placeholders, by design |
| `SOURCES.md` | the trace-or-delete registry for this lane | filled |

## Class, honestly labelled

By the harness catalogue's grouping this is an **external, adjacent-class** lane: the upstream work has an
objective (mean core bits per byte at equal training tokens against a fixed-order anchor, lower is better;
stored bytes as the tie-break) and pre-registered decision rules, separate-context review, a chronicle and a
kill ledger. It has no hash-drawn witness set, no advancing `frontier.json` and no κ seal. The markers here
are not filled with prose to make a gate pass: a harness that grades nothing would still say VALIDATED.

## What this lane does not do

- It does not list the upstream work in the harness catalogue (`HARNESS_PATHS.md`). That entry is by
  invitation and waits on the owner's answer; the draft is §11 of the overlap note.
- It does not publish the acknowledgement paragraph of the note's §10 until the owner chooses a name.
- It does not touch the upstream repository. `main` on this fork tracks upstream `main`; contributions
  go upstream only as pull requests the owner reviews.

## Where the harness is

- Engine, constitution, catalogue: https://github.com/mitchuski/agentprivacy-harness
- Method reference and the model it derives from: https://agentprivacy.ai/guide/the-dual-agent-harness · https://agentprivacy.ai/model
- Community front: https://mages.city

Licence of this directory: CC BY 4.0 for documents, MIT for any code, matching the upstream split.
