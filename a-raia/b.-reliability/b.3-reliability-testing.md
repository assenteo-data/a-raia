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
---

# B.3 Reliability testing

Test the system for accuracy, bias and robustness.

| Control # | Control                                                                                                     | Source                                          | Primary owner | Supporting functions |
| --------- | ----------------------------------------------------------------------------------------------------------- | ----------------------------------------------- | ------------- | -------------------- |
| B.3.i     | Test the system and its training data for bias that could lead to discrimination, and audit this regularly. | Enterprise vendor requirement                   | AI/ML         | Legal & Privacy      |
| B.3.ii    | Decide how you'll measure output accuracy, do it, and write it down.                                        | Enterprise vendor requirement                   | AI/ML         | Engineering          |
| B.3.iii   | Check for and fix data errors, gaps and bias risks.                                                         | Art 10 – Data and data governance               | AI/ML         | Engineering          |
| B.3.iv    | Test robustness under normal conditions and under foreseeable stress and error scenarios.                   | Art 15 – Accuracy, robustness and cybersecurity | Engineering   | AI/ML, Security      |
| B.3.v     | After launch, keep collecting and reviewing performance and risk information (post-deployment monitoring).  | Art 72 – Post-market monitoring                 | Engineering   | AI/ML, Product       |
| B.3.vi    | Check and record whether your datasets are relevant and representative, and note any known biases.          | Art 10 – Data and data governance               | AI/ML         | Legal & Privacy      |
