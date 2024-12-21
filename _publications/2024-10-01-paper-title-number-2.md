---
title: "Policy-regularized Offline Safe Reinforcement Learning with Preference Aligned Sampling"
collection: publications
category: projects
permalink: /publication/2024-10-01-paper-title-number-2
excerpt: 'This project is about offline Safe reinforcement learning. Work was done when Cheng in CMU.'
slidesurl: 'http://tangchengtsinghua.github.io/files/chengtang.pdf'
paperurl: 'http://tangchengtsinghua.github.io/files/Policy-regularized%20Offfine%20Safe%20Reinforcement%20Learning%20with%20Preference.pdf'
---

Offfine safe reinforcement learning (RL) aims to learn a safe and relatively rewarding policy with a
precollected dataset. One prevalent method to deal with this problem is offfine policy-regularized
method, which typically incorporates a behavior cloning mechanism into the policy learning to
regularize the learned policy stay close enough to the behavior policy, hence mitigates the distribution
shift challenge. However, this framework may suffer from suboptimality of behavior policy due to
the imbalanced dataset. In this work, we propose DIAM (distribution aligned sampling), a preference
aligned sampling method customized for policy-regularized offfine safe algorithms. Comprehensive
evaluation in various tasks illustrates the ability of DIAM in optimizing the behavior policy, hence
beneffts policy-regularized offfine safe algorithms. DIAM shows superiority compared to other
model-centric method and data-centric method, making it more applicable and universal, even with
simple structure.