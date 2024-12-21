---
title: "Robust Offline Reinforcement Learning with Linearly Structured f-Divergence Regularization"
collection: projects
category: manuscripts
permalink: /publication/2024-10-01-paper-title-number-2.md
excerpt: 'This paper is about offline Safe reinforcement learning'
date: 2024-11-27
venue: 'ArXiv'
slidesurl: 'http://tangchengtsinghua.github.io/files/RRMDP_presentation.pdf'
paperurl: 'https://arxiv.org/abs/2411.18612'
citation: 'Cheng Tang, Zhishuai Liu and Pan Xu. Robust Offline Reinforcement Learning with Linearly Structured f-Divergence Regularization. arXiv preprint 2411.18612, 2024.'
---

The Distributionally Robust Markov Decision Process (DRMDP) is a popular framework for addressing dynamics shift in reinforcement learning by learning policies robust to the worst-case transition dynamics within a constrained set. However, solving its dual optimization oracle poses significant challenges, limiting theoretical analysis and computational efficiency. The recently proposed Robust Regularized Markov Decision Process (RRMDP) replaces the uncertainty set constraint with a regularization term on the value function, offering improved scalability and theoretical insights. Yet, existing RRMDP methods rely on unstructured regularization, often leading to overly conservative policies by considering transitions that are unrealistic. To address these issues, we propose a novel framework, the d-rectangular linear robust regularized Markov decision process (d-RRMDP), which introduces a linear latent structure into both transition kernels and regularization. For the offline RL setting, where an agent learns robust policies from a pre-collected dataset in the nominal environment, we develop a family of algorithms, Robust Regularized Pessimistic Value Iteration (R2PVI), employing linear function approximation and f-divergence based regularization terms on transition kernels. We provide instance-dependent upper bounds on the suboptimality gap of R2PVI policies, showing these bounds depend on how well the dataset covers state-action spaces visited by the optimal robust policy under robustly admissible transitions. This term is further shown to be fundamental to d-RRMDPs via information-theoretic lower bounds. Finally, numerical experiments validate that R2PVI learns robust policies and is computationally more efficient than methods for constrained DRMDPs