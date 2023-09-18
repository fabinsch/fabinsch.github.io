---
title: "Reactive Stepping for Humanoid Robots using Reinforcement Learning: Application to Standing Push Recovery on the Exoskeleton Atalante"
collection: publications
authors: 'Alexis Duburcq, <b>Fabian Schramm</b>, Guilhem Boéris, Nicolas Bredeche, Yann Chevaleyre'
video: 'https://www.youtube.com/watch?v=HLx6CHfpmBM'
permalink: /publication/2022-03-01-reactive-stepping
excerpt: 'This paper presents a reinforcement learning framework capable of learning robust standing push recovery for bipedal robots with a smooth out-of-the-box transfer to reality, requiring only instantaneous proprioceptive observations.'
date: 2022-03-01
venue: '2022 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
paperurl: 'https://arxiv.org/abs/2203.01148'
citation: 'Duburcq et al. (2022). &quot;Reactive Stepping for Humanoid Robots using Reinforcement Learning: Application to Standing Push Recovery on the Exoskeleton Atalante.&quot; <i>IROS22</i>.'
---
State-of-the-art reinforcement learning is now able to learn versatile locomotion, balancing and push-recovery capabilities for bipedal robots in simulation. Yet, the reality gap has mostly been overlooked and the simulated results hardly transfer to real hardware. Either it is unsuccessful in practice because the physics is over-simplified and hardware limitations are ignored, or regularity is not guaranteed and unexpected hazardous motions can occur. This paper presents a reinforcement learning framework capable of learning robust standing push recovery for bipedal robots with a smooth out-of-the-box transfer to reality, requiring only instantaneous proprioceptive observations. By combining original termination conditions and policy smoothness conditioning, we achieve stable learning, sim-to-real transfer and safety using a policy without memory nor observation history. Reward shaping is then used to give insights into how to keep balance. We demonstrate its performance in reality on the lower-limb medical exoskeleton Atalante.

[Video](https://www.youtube.com/watch?v=HLx6CHfpmBM)

[Download paper here](https://arxiv.org/pdf/2203.01148.pdf)