# Development status

Updated 19 November 2026.

## Demonstrated today

The current prototype can render lessons from structured plans using a common animation engine. Controllers compute the state and visible results. Narration slots take their values from the same state, and the compiler checks the plan before rendering it.

The demonstration includes logic, reactions, phase changes, optics, accounting, and growth or decay. The video exports preserve the frozen golden lesson timelines. The supporting images show the start, middle, and end of each chapter.

## Evidence at this milestone

| Check | Recorded result |
|---|---|
| Hand-authored golden lessons | 7 lessons, 21 chapters |
| Golden Python checks | 7 passed |
| Golden Dart overlap checks | 7 passed |
| Internal truth and stage-fidelity judging | 7 passed |
| Full topic coverage of goldens | 4 passed, 3 have coverage gaps |
| Tools test rerun on 16 November | 595 passed, 1 known stale atom-kit retiming failure |

The saved judge results were reused when their narration and stage-description inputs were byte-identical. Internal judging and engineering tests establish the demonstrated behavior. Learning outcomes with students remain to be evaluated.

## Automatic planning experiment

The same engine is being tested with lesson scripts from language models. Every candidate must pass deterministic checks, judging, and visual review. A full lesson additionally needs topic coverage.

| Cohort | Topics finished | Chapters accepted by gates | Chapters surviving visual review | Full lessons surviving review and coverage |
|---|---:|---:|---:|---:|
| Lite, original prompt | 7 / 7 | 2 | 0 | 0 |
| Lite, revised prompt | 7 / 7 | 5 | 1 | 0 |
| Flash, revised prompt | 5 / 7 | 12 | 7 | 0 |

The Flash comparison is incomplete. Its half-life and refraction topics are pending after provider service and quota errors. A candidate's gate acceptance can still be overturned by visual review. Current findings include grammar around computed slots, a binding counter whose layers overlap, and incomplete topic coverage.

The seven golden videos demonstrate hand-authored plans. Their quality should be assessed alongside the automatic-generation results above.

## Coverage still to build

- Enzyme action needs broader treatment of denaturation, inhibitors, and the effects of pH or temperature.
- The golden business-liability lesson needs taxation, registration processes, and legal distinctions beyond liability protection. The automatically planned liability lesson also missed ownership structure, share issuance, and profit distribution.
- The golden half-life lesson's stage descriptions need explicit carbon dating and isotope identification, including carbon-14.

## Next milestone

Finish the current comparison, resolve the rendering and grounding defects revealed by review, and produce complete automatically planned lessons that pass the same gates as the goldens. Broader curriculum rollout and evaluation with learners follow that milestone.

The exact snapshot behind these tables is in [validation.json](evidence/validation.json). The media fingerprints are in [assets.sha256](evidence/assets.sha256).
