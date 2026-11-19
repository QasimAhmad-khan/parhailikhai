# Parhai Likhai — progress and proof

*Evidence snapshot: 19 November 2026.*

**Parhai Likhai has progressed from slide fallback to an animation engine that demonstrates working processes across seven lesson topics.** A learner can watch switches drive a lamp, an enzyme reject the wrong substrate and release products, or water change phase while its temperature curve holds through melting and boiling.

The public showcase contains **21 chapters, 168 narrated beats, and 13 minutes 17 seconds of full-lesson video**. Every golden lesson includes a mechanism, a concrete analogy, and a worked example. [Watch the demonstrations](https://qasimahmad-khan.github.io/parhailikhai/) · [Verified totals](evidence/progress.json)

## What is working today

| Demonstrated milestone | Evidence |
|---|---|
| **7 golden lessons / 21 chapters** | All seven passed saved compilation checks, rendered-overlap checks, and internal truth and visual-fidelity judging. [Results](evidence/validation.json) |
| **168 narrated beats** | Each golden lesson contains three chapters with eight narration events each. [Totals](evidence/progress.json) |
| **7 full-lesson videos + a short walkthrough** | Over 13 minutes of lesson footage, with on-screen narration. [Media measurements](evidence/media.json) |
| **63 sample frames / 7 contact sheets** | Start, middle, and end of every chapter are available for inspection. [Visual evidence](images/) |
| **Phone and desktop checks** | Golden overlap validation passed at 390 px and 1280 px. [Validation](evidence/validation.json) |
| **595 passing tools tests** | The latest recorded rerun also has one known stale legacy-kit failure. [Recorded verification](evidence/progress.json) |
| **1,536 archived planner responses replayed** | The regression run recorded 210 deterministic passes and 1,326 rejections, without new planner calls. [Replay totals](evidence/progress.json) |

The goldens are hand-authored demonstration plans rendered by the engine. **Four also passed full topic-coverage judging**; three demonstrate a narrower slice of their topics. Internal judging and visual review establish the recorded demonstration quality. Student learning outcomes have not yet been measured. [Per-lesson scope](evidence/validation.json)

## The development journey

| Milestone | What the evidence established |
|---|---|
| **An existing lesson library was audited** | The earlier inventory covered 26 lesson packages and 125 concepts. Of 115 animated concepts measured at both screen widths, 66 had findings. This audit established a concrete quality baseline for the legacy library. |
| **A broad benchmark exposed the starting limit** | In a frozen 24-topic benchmark, 23 topics took the slide fallback; the remaining topic failed compilation. The limitation was recorded before general-engine development. |
| **Early general-generation trials produced no complete pass** | The first three-topic trial finished at 0/3. Compiler repairs subsequently recovered 3 of 18 saved responses without new model calls. |
| **The engine began operating the subject process** | The first hand-authored operating benchmark delivered three lessons and nine chapters with zero recorded Python/Dart gate findings. It was inspected in 54 real-player frames across phone and desktop. |
| **The golden benchmark expanded** | The current seven lessons span biology, logic, thermal physics, optics, accounting, business liability, and radioactive decay, with 21 chapters and 168 narrated beats. |
| **An automatically generated full lesson survived review** | An earlier enzyme trial produced a complete three-chapter lesson that passed internal truth, fidelity, and coverage judging and survived visual review. Recorded API planning cost was **$0.0216**, approximately **2.2¢**, for that attempt. This is a historical result under that run's engine and checks. |

[Milestone records and source fingerprints](evidence/progress.json). Historical results retain their original scope. The 24-topic baseline and the seven-topic golden showcase use different sets and authoring methods, so they do not establish a like-for-like benchmark improvement rate. Earlier acceptance can be overturned as checks become stricter.

The 2.2¢ figure covers that lesson's planner requests, including repairs and read-back. It excludes separate judging, narration audio, hosting, and engineering work; it is a measured attempt cost rather than a production unit-cost forecast.

## What the stage can demonstrate

| Golden lesson | Visible teaching evidence | Recorded moving layers |
|---|---|---:|
| [AND and OR gates](images/logic-contact-sheet.jpg) | Input switches, signal paths, lamp, and truth table agree. Badge/PIN access controls a door; sensors drive an alarm. | 17 |
| [Enzyme action](images/enzyme-contact-sheet.jpg) | A matching substrate docks and splits, products leave, the enzyme is reused, and a wrong fit is rejected. | 35 |
| [Heating curve](images/heating-contact-sheet.jpg) | Particles vibrate, slide, and escape. The graph and temperature readout follow the same phase changes and plateaus. | 35 |
| [Refraction](images/refraction-contact-sheet.jpg) | Rays respond to optical inputs. A cart crossing surfaces gives the analogy; the worked example demonstrates total internal reflection. | 88 |
| [Bank reconciliation](images/ledger-contact-sheet.jpg) | Transactions update the two records and the computed difference between them. | 24 |
| [Business liability](images/liability-contact-sheet.jpg) | Debts affect business and personal funds differently across the demonstrated ownership cases. | 36 |
| [Radioactive half-life](images/half_life-contact-sheet.jpg) | Elapsed time, remaining quantities, the decay curve, and the schematic nuclei display advance together. | 4 |

These lessons contain **239 recorded moving layers** in total. Layer counts describe scene construction; the videos and review results establish what those movements teach. [Per-lesson validation](evidence/validation.json)

## Automatic-generation evidence

The engine has also been tested with model-authored lesson plans. The latest frozen comparison records:

| Cohort | Topics finished | Chapters accepted by gates | Chapters surviving visual review | Complete lessons surviving review and coverage |
|---|---:|---:|---:|---:|
| Lite, original prompt | 7 / 7 | 2 | 0 | 0 |
| Lite, revised prompt | 7 / 7 | 5 | 1 | 0 |
| Flash, revised prompt | 5 / 7 | 12 | 7 | 0 |

Flash's five completed topics yielded seven chapters that survived review. Across the three cohorts, **all 19 gate-accepted chapters were inspected on phone and desktop**, using **22 sheets and 114 frames**. The Flash cohort remains incomplete. Its results establish accepted chapter examples, while reliable complete-lesson generation remains unproven in this latest comparison. [Comparison snapshot](evidence/validation.json) · [Review totals](evidence/progress.json)

The public evidence supports a concrete milestone: **a working animation engine with seven inspectable golden demonstrations and recorded examples of automatically generated teaching content**. The demonstrations, historical automatic success, and current experimental results are identified separately so each claim can be assessed on its own evidence.
