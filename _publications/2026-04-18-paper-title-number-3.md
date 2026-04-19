---
title: "MedQPA-Gen: Medical Question Proposing and Answering for Report Generation"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-3
excerpt: 'This paper is about medical report generation'
date: 2026-4-19
venue: 'Published on ACL Findings'
citation: 'Weijie Liang*, Xiyue Zhu*†, Ruike Zhu, Chenhao Li, Cheng Tang, Zhiyu Liu, Zhihua Gong, Shirui Luo, Yudu Li, Volodymyr Kindratenko.'
---

Medical report generation from medical im-
ages is a vital AI task that helps doctors with
diagnosis and marks a significant step toward
creating general AI-powered medical systems.
However, previous methods either fail to op-
timize factual accuracy or heavily depend on
expert preference data. To overcome these chal-
lenges, we propose MedQPA, an automatic
and generalizable report evaluation technique
that uses question proposing and answering
to enable controllable, structured reasoning
grounded in medical domain knowledge and
the factual correctness of the report. Addi-
tionally, we design MedQPA-Gen, a medical
report generation pipeline that maximizes the
MedQPA score through prompt engineering
and reinforcement learning with MedQPA as a
reward signal. We demonstrate that MedQPA
is an accurate evaluation metric that closely
correlates with human preferences. More
importantly, MedQPA-Gen achieves higher
human preference scores and better perfor-
mance on downstream tasks. We open-source
code at this repo https://github.com/MedQPA-
gen/MedQPA-gen