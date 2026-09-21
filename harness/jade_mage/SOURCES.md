# Sources

Trace or delete (GR-9): nothing is citable unless it resolves through this
registry to a concrete path or reference. Paths are relative to this directory.

Evidence classes:

- **E-RUN** — output produced in this lane; path to the run dir or log.
- **E-DOC** — a document in this repository; path.
- **E-EXT** — external source; stable reference (URL, DOI, spec name).

| slug | class | resolves to | note |
|---|---|---|---|
| upstream-repo | E-EXT | https://github.com/JadeZaher/ternary-memory-research | the artifact this lane reads; reviewed at `35c65bd` (2026-09-20) |
| discovery-protocol | E-EXT | https://agentprivacy.org/discovery.md | the survey the owner ran (v0.3, still current 2026-09-21); their copy at `../../sources/user/orientation-protocol-v0.3.txt` |
| their-orientation | E-DOC | `../../research/agentprivacy-orientation.md` | the completed survey, 2026-09-12 UTC |
| their-audit | E-DOC | `../../research/hardening-2026-09-18-heldout.md` | the held-out self-audit and the pre-registered rule (§13) |
| their-general-track | E-DOC | `../../research/general-model-track.md` | the locked qualification rule (§5) and night-1 result (§6) |
| overlap-note | E-DOC | `../../sources/agentprivacy/OVERLAP_NOTE_2026-09-21.md` | the note delivered upstream by pull request |
| carrier-symmetry | E-DOC | `../../research/carrier-symmetry.md`, `../../experiments/verify_carrier_symmetry.py`, `../../outputs/carrier-symmetry.json` | the first contribution (PR-1 of the note's §9) plus the same-day follow-up (differential-pair reading, §3b); 33 exhaustive checks |
| first-contact | E-RUN | `chronicles/2026-09-21_first-contact.md` | what happened on this side, in order |
| harness-catalogue | E-EXT | https://github.com/mitchuski/agentprivacy-harness/blob/main/HARNESS_PATHS.md | where an accession would be written, on invitation only |
| skill-catalog | E-EXT | https://skills.agentprivacy.ai/assets/skillsync/catalog.json | the packet catalog the owner hash-checked; the `dual-agent-harness` v1.0 home-path defect they surfaced is ours to fix |
