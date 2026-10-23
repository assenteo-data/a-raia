---
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
tags:
  - reliability
  - engineering
  - ai-ml
  - security
---

# B.2 Reliability design

Design the system to stay stable and perform well over time.

| Control # | Control                                                                                                                                                                                                                        | Source                                          | Primary owner | Supporting functions     |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------- | ------------- | ------------------------ |
| B.2.i     | Set up data governance for your training, validation and testing datasets. (If you don't develop your own model, you should retrieve this information from the third-party model provider.)                                    | Art 10 – Data and data governance               | AI/ML         | Legal & Privacy          |
| B.2.ii    | Document where your datasets come from, how they were collected and how they were prepared (data provenance). (If you don't develop your own model, you should retrieve this information from the third-party model provider.) | Art 10 – Data and data governance               | AI/ML         | Legal & Privacy          |
| B.2.iii   | Explain which models you use, whether you built, sourced or licensed them, and the reasoning behind this decision.                                                                                                             | Principle 7 – Original Framework                | AI/ML         | Leadership, Engineering  |
| B.2.iv    | Set performance and accuracy targets that fit what the system is for.                                                                                                                                                          | Art 15 – Accuracy, robustness and cybersecurity | AI/ML         | Product                  |
| B.2.v     | Put safeguards in place against performance degradation, model drift and adversarial manipulation.                                                                                                                             | Art 15 – Accuracy, robustness and cybersecurity | AI/ML         | Security, Engineering    |
| B.2.vi    | Apply cybersecurity controls that fit your AI models and data.                                                                                                                                                                 | Art 15 – Accuracy, robustness and cybersecurity | Security      | Engineering              |
| B.2.vii   | Use change management and version control for your AI systems and models.                                                                                                                                                      | Art 17 – Quality management system              | Engineering   | AI/ML                    |
| B.2.viii  | Design the system to prevent harm, for example by screening inputs and outputs, and, where relevant, add feedback and supervision mechanisms.                                                                                  | Art 17 – Quality management system              | AI/ML         | Product, Legal & Privacy |
