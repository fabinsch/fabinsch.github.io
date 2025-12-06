---
title: "First-order Sobolev Reinforcement Learning"
collection: publications
authors: '<b>Fabian Schramm</b>, Nicolas Perrin-Gilbert, Justin Carpentier'
permalink: /publication/2025-10-31-sobolev-rl
excerpt: 'We propose a refinement of temporal-difference learning that enforces first-order Bellman consistency by training the value function to match both Bellman targets and their derivatives.'
date: 2025-10-31
venue: 'Workshop on Differentiable Systems and Scientific Machine Learning, EurIPS 2025'
paperurl: 'https://arxiv.org/abs/2511.19165'
citation: 'Schramm, F., Perrin-Gilbert, N., & Carpentier, J. (2025). &quot;First-order Sobolev Reinforcement Learning.&quot; <i>Workshop on Differentiable Systems and Scientific Machine Learning, EurIPS 2025</i>.'
---
We propose a refinement of temporal-difference learning that enforces first-order Bellman consistency: the learned value function is trained to match not only the Bellman targets in value but also their derivatives with respect to states and actions. By differentiating the Bellman backup through differentiable dynamics, we obtain analytically consistent gradient targets. Incorporating these into the critic objective using a Sobolev-type loss encourages the critic to align with both the value and local geometry of the target function. This first-order TD matching principle can be seamlessly integrated into existing algorithms, such as Q-learning or actor-critic methods (e.g., DDPG, SAC), potentially leading to faster critic convergence and more stable policy gradients without altering their overall structure.

[Download paper here](https://arxiv.org/abs/2511.19165)