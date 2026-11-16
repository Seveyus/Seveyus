## Yoann Frayce

AI engineer and founder. I build machine-learning models and the software
around them, for decisions made under uncertainty: forecasting, graph learning,
simulation, agents, multimodal and local AI.

Two rules run through the work below. In machine learning, the baseline is the
one a practitioner would actually reach for, the protocol is fixed before the
test is scored, and results that do not flatter stay in. In software, a language
model may read, explain and narrate, but it must not produce the number someone
acts on: the arithmetic belongs in deterministic code, and the boundary belongs
in tests rather than in prompt wording.

### Current product work

**FleetMind** — simulation-driven decision systems for EV fleet operations.
Private development; technical case study available on my [portfolio][portfolio].

### Selected work · machine learning

| Project | What it is, and what it found | Role |
|---|---|---|
| [Weather-Intelligence-Metseo](https://github.com/Seveyus/Weather-Intelligence-Metseo) | Forecasts every sensor of a weather station from +1 to +72 h using only its own measurements. Learned on 881 Météo-France stations and scored once on 133 it never saw: a neural network and boosted trees finish within 2%, and the trees win the pre-registered score. Correcting six global weather models cuts their wind error by 17% at +24 h. | Sole author |
| [agent-fabric](https://github.com/Seveyus/agent-fabric) | A 1.39M-node temporal graph of pull requests, people and repositories, built to test whether relational structure beats hand-built features. On its own the graph is worth +0.043 AUC over an identical MLP; on top of LightGBM with history aggregates it adds +0.0075, for about 200× the training cost. | Sole author |
| [hello-worlds](https://github.com/Tariolle/hello-worlds) | Geometry-aware world models for EEG. Pretrain, freeze, linear-probe — a controlled ablation whose honest answer was a null. Finalist, Hack the World(s) 2026. | 1 of 4 · owned the three-geometry world model, the event-transfer pipeline and the results figures |

### Selected work · software engineering

| Project | What it is | Role |
|---|---|---|
| [Obligation-Ledger-AI](https://github.com/Seveyus/Obligation-Ledger-AI) | Air-gapped contract RAG. Every value quotes its source page, verified in Python; every derived date recomputed in code. | Sole author of the retrieval service · 1 of 4 on the product |
| [SimForge](https://github.com/Seveyus/SimForge) | Natural language to executable simulation, run in an isolated sandbox and forked into competing interventions. | Primary author · simulation, sandbox execution, decision engine |
| [Omnivision](https://github.com/Atharva322/Omnivision) | Audio-first assistant for blind wearers of smart glasses, built so it only asserts what it has direct evidence for. | 1 of 6 · owned the extraction and evidence layer |
| [Lecture → Living Mind-Map](https://github.com/Renanlvrt/No-excuse-to-not-go-to-lectures-anymore) | Speech becomes an interactive concept map while the lecture is still running. Built hands-free, while running. | 1 of 3 · owned the realtime transcript path and the comprehension levels |
| [agent-sandbox](https://github.com/Seveyus/agent-sandbox) | Three scheduled agents that read issues, write code, review each other, and distil what they learned. Every pull request was opened without a prompt. | Operated and documented. The agent framework is [Union.ai's](https://github.com/unionai-oss/flyte-agent-loop), not mine. |

Private, with case studies on the portfolio: [DepotOps][depotops] (First Place,
Crusoe Track, RAISE Hackathon) and [Forkcast][forkcast] (Best Solo Hacker,
VSLive! Hack-a-thon).

### Elsewhere

[Portfolio][portfolio] · yoann.frayce.dev@gmail.com

<!-- The site URL lives in the link definitions below. -->
[portfolio]: https://yoannfrayce.pages.dev
[depotops]: https://yoannfrayce.pages.dev/work/depotops
[forkcast]: https://yoannfrayce.pages.dev/work/forkcast
