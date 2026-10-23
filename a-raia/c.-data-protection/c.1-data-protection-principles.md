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
  - data-protection
  - engineering
  - ai-ml
  - legal-and-privacy
---

# C.1 Data protection principles

Handle data in the AI system using industry-standard data protection principles, with controls in place to minimise data risk.

| Control # | Control                                                                                                                       | Source                            | Primary owner   | Supporting functions          |
| --------- | ----------------------------------------------------------------------------------------------------------------------------- | --------------------------------- | --------------- | ----------------------------- |
| C.1.i     | Classify the data you handle, including personal data and company data.                                                       | Enterprise vendor requirement     | Legal & Privacy | Security                      |
| C.1.ii    | Only collect and use the personal data you need, for the purpose you collected it (data minimisation and purpose limitation). | Enterprise vendor requirement     | Legal & Privacy | Product, Engineering          |
| C.1.iii   | Keep personal data out of training and testing datasets wherever you can.                                                     | Art 10 – Data and data governance | AI/ML           | Legal & Privacy               |
| C.1.iv    | Set and follow retention schedules, and delete or anonymise personal data when you no longer need it.                         | Enterprise vendor requirement     | Legal & Privacy | Engineering                   |
| C.1.v     | Use anonymisation and/or pseudonymisation that fits the risk, and document how.                                               | Enterprise vendor requirement     | Engineering     | Legal & Privacy, Security     |
| C.1.vi    | Have processes and tools to handle data subject rights requests (e.g. access, deletion, objection).                           | Enterprise vendor requirement     | Legal & Privacy | Engineering, Customer Success |
