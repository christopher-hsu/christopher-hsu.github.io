---
layout: post
title:  "Active Scout: Multi-Target Tracking using Neural Radiance Fields in Dense Urban Environments"
date:   2024-06-10 22:21:59 +00:00
image: images/philly_tpv_119.png
categories: research
authors: "<strong>Christopher D. Hsu</strong> and Pratik Chaudhari"
venue: "IEEE/RSJ International Conference of Intelligent Robotics and Systems (IROS)"
paper: https://arxiv.org/abs/2406.07431
code: https://github.com/grasp-lyrl/ActiveScout
---

We study pursuit-evasion games in highly occluded urban environments, e.g. tall buildings in a city, where a scout (quadrotor) tracks multiple dynamic targets on the ground. We show that we can build a neural radiance field (NeRF) representation of the city -- online -- using RGB and depth images from different vantage points. This representation is used to calculate the information gain to both explore unknown parts of the city and track the targets -- thereby giving a completely first-principles approach to actively tracking dynamic targets. We demonstrate, using a custom-built simulator using Open Street Maps data of Philadelphia and New York City, that we can explore and locate 20 stationary targets within 300 steps. This is slower than a greedy baseline which which does not use active perception. But for dynamic targets that actively hide behind occlusions, we show that our approach maintains, at worst, a tracking error of 200m; the greedy baseline can have a tracking error as large as 600m. We observe a number of interesting properties in the scout's policies, e.g., it switches its attention to track a different target periodically, as the quality of the NeRF representation improves over time, the scout also becomes better in terms of target tracking. 