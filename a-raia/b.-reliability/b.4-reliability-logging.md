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

# B.4 Reliability logging

Log what the system does automatically, so inputs, outputs and actions can be traced.

| Control # | Control                                                                                                 | Source                              | Primary owner | Supporting functions         |
| --------- | ------------------------------------------------------------------------------------------------------- | ----------------------------------- | ------------- | ---------------------------- |
| B.4.i     | Automatically log system activity so inputs, outputs and actions are traceable.                         | Art 12 – Record-keeping and logging | Engineering   | Security                     |
| B.4.ii    | Set how long you keep logs and store them securely (log retention).                                     | Art 12 – Record-keeping and logging | Security      | Legal & Privacy, Engineering |
| B.4.iii   | Make sure logs can be accessed for audits, investigations and oversight.                                | Art 12 – Record-keeping and logging | Engineering   | Security                     |
| B.4.iv    | Protect logs from being changed or deleted: keep them immutable and limit access to people who need it. | Art 12 – Record-keeping and logging | Security      | Engineering                  |
| B.4.v     | Version your datasets so you can trace which data was used to build and evaluate each model.            | Art 10 – Data and data governance   | AI/ML         | Engineering                  |
