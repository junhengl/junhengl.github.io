---
title: "Kinodynamics-based Pose Optimization for Humanoid Loco-manipulation"
collection: publications
permalink: /publication/2023UnifiedMPC
date: 2023-12-16
excerpt: "Authors: Junheng Li and Quan Nguyen<br/><img src='/images/boxpushing.gif'>"
paperurl: 'https://arxiv.org/abs/2303.04985'
venue: 'IEEE-RAS International Conference on Humanoid Robots (HUMANOIDS) 2023'
---

Abstract: This paper presents a novel approach for controlling humanoid robots to push heavy objects. The approach combines kinodynamics-based pose optimization and loco-manipulation model predictive control (MPC). The proposed pose optimization considers the object-robot dynamics model, robot kinematic constraints, and object parameters to plan the optimal pushing pose for the robot. The loco-manipulation MPC is used to track the optimal pose by coordinating pushing and ground reaction forces, ensuring accurate manipulation and stable locomotion. Numerical validation demonstrates the effectiveness of the framework, enabling the humanoid robot to push objects with various parameter setups. The pose optimization can be solved as a nonlinear programming (NLP) problem within an average of 250 ms. The proposed control scheme allows the humanoid robot to push objects weighing up to 20 kg (118% of the robot's mass). Additionally, it can recover the system from a 120 N lateral force disturbance applied for 0.3 s.