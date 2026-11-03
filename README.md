# bubble — team workspace

Team `bubble` for **Machine Learning (IC-PBL), 2025-Fall**, Hanyang University
ERICA (Prof. Yongjae Yoo, industry mentor Dr. Young Hoon Ji, Hexar Humancare).

This repository holds the team-level deliverables: the written report and the
mentoring documents. The code lives in two separate repositories.

| repository | contents |
|---|---|
| [machine-learning](https://github.com/lmm0125-art/machine-learning) | the classifier: source, tests, evaluation, report in Markdown |
| [roomi](https://github.com/lmm0125-art/roomi) | 루미 prototype — separate IC-PBL project (2026-2) by the same author |

## Deliverables in this repository

| file | what it is |
|---|---|
| [`docs/Final report bubble.docx`](docs/Final%20report%20bubble.docx) | final report, submitted 2025-12-16 |
| `docs/[위밋프로젝트] 멘토링보고서양식_hwp로 제출(기계학습).hwp` | We-Meet mentoring report |
| [`CONTRIBUTORS.md`](CONTRIBUTORS.md) | who did what |

The same report, in a form that can be reviewed line by line on GitHub, is at
[`machine-learning/docs/REPORT.md`](https://github.com/lmm0125-art/machine-learning/blob/main/docs/REPORT.md).
It carries the measured numbers, the four figures and the references; the `.docx`
here is the submitted artefact.

## Team

| member | role |
|---|---|
| WANG YUMING | project scheduling and coordination |
| 우시시 | data pipeline and visualisation |
| 이멍멍 | model and training pipeline |
| 유열 | report and mentor documentation |

## Result in one line

A small LSTM with masked attention pooling classifies five rehabilitation
exercises at **0.931 ± 0.091** accuracy per recording under stratified 5-fold
group cross-validation, and produces a per-timestep attention map that can be
inspected next to the trajectory.
