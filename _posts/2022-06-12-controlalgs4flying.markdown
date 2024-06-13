---
layout: post
title:  "Control algorithms for guidance of autonomous flying agents using reinforcement learning"
date:   2022-06-12 22:21:59 +00:00
image: images/ma6_rlpronav.pdf
categories: research
authors: "<strong>Christopher D. Hsu</strong>, Franklin J. Shedleski, and Bethany Allik"
venue: "SPIE Defense and Commerical Sensing (SPIE)"
paper: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12544/1254407/Control-algorithms-for-guidance-of-autonomous-flying-agents-using-reinforcement/10.1117/12.2663072.short#_=_
# code: https://github.com/grasp-lyrl/Model4MAInteractions
---

In this paper, we explore the advantages and disadvantages of the traditional guidance law, proportional navigation (ProNav), in comparison to a reinforcement learning algorithm called proximal policy optimization (PPO) for the control of an autonomous agent flying to a target. Through experiments with perfect state estimation, we find that the two strategies under control constraints have their own unique benefits and tradeoffs in terms of accuracy and the resulting bounds on the reachable set of acquiring targets. Interestingly, we discover that it is the combination of the two strategies that results in the best overall performance. Lastly, we show how this policy can be extended to guide multiple agents.