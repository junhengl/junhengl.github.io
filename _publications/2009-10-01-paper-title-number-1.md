---
title: "Continuous Dynamic Bipedal Jumping via Adaptive-Model Optimization"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: "Authors: Junheng Li, Omar Kolt, and Quan Nguyen<br/><img src='/images/continuousJumping.gif'>"
paperurl: 'https://arxiv.org/abs/2404.11807'
---

Abstract: Dynamic and continuous jumping remains an open yet challenging problem in bipedal robot control. The choice of dynamic models in trajectory optimization (TO) problems plays a huge role in trajectory accuracy and computation efficiency, which normally cannot be ensured simultaneously. In this letter, we propose a novel adaptive-model optimization approach, a unified framework of Adaptive-model TO and Adaptive-frequency Model Predictive Control (MPC), to effectively realize continuous and robust jumping on HECTOR bipedal robot. The proposed Adaptive-model TO fuses adaptive-fidelity dynamics modeling of bipedal jumping motion for model fidelity necessities in different jumping phases to ensure trajectory accuracy and computation efficiency. In addition, conventional approaches have unsynchronized sampling frequencies in TO and real-time control, causing the framework to have mismatched modeling resolutions. We adapt MPC sampling frequency based on TO trajectory resolution in different phases for effective trajectory tracking. In hardware experiments, we have demonstrated robust and dynamic jumps covering a distance of up to 40 cm (57% of robot height). To verify the repeatability of this experiment, we run 53 jumping experiments and achieve 90% success rate. In continuous jumps, we demonstrate continuous bipedal jumping with terrain height perturbations (up to 5 cm) and discontinuities (up to 20 cm gap).
