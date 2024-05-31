---
title: "Dynamic Walking of Bipedal Robots on Uneven Stepping Stones via Adaptive-frequency MPC"
collection: publications
permalink: /publication/2023AdaptiveFreqMPC
date: 2023-01-01
excerpt: "Authors: Junheng Li and Quan Nguyen<br/><img src='/images/adaptiveFreqMPC.gif'>"
paperurl: 'https://arxiv.org/abs/2209.08664'
venue: 'IEEE Control Systems Letters (L-CSS) and American Control Conference 2023'
---

Abstract: This paper presents a novel Adaptive-frequency MPC framework for bipedal locomotion over terrain with uneven stepping stones. In detail, we intend to achieve adaptive foot placement and gait period for bipedal periodic walking gait with this MPC, in order to traverse terrain with discontinuities without slowing down. We pair this adaptive-frequency MPC with a kino-dynamics trajectory optimization for optimal gait periods, center of mass (CoM) trajectory, and foot placements. We use whole-body control (WBC) along with adaptive-frequency MPC to track the optimal trajectories from the offline optimization. In numerical validations, our adaptive-frequency MPC framework with optimization has shown advantages over fixed-frequency MPC. The proposed framework can control the bipedal robot to traverse through uneven stepping stone terrains with perturbed stone heights, widths, and surface shapes while maintaining an average speed of 1.5 m/s