---
layout: post
title:  "A Model for Perimeter Defense Problems with Heterogeneous Teams"
date:   2024-04-04 22:21:59 +00:00
image: images/shapefig1.png
categories: research
authors: "<strong>Christopher D. Hsu</strong>, Mulugeta A. Haile, and Pratik Chaudhari"
venue: "American Controls Conference (ACC)"
paper: https://arxiv.org/abs/2208.01430
code: https://github.com/grasp-lyrl/Model4MAInteractions
---

We introduce a model for multi-agent interaction problems to understand how a heterogeneous team of agents should organize its resources to tackle a heterogeneous team of attackers. This model is inspired by how the human immune system tackles a diverse set of pathogens. The key property of this model is "cross-reactivity" which enables a particular defender type to respond strongly to some attackers but weakly to a few different types of attackers. Due to this, the optimal defender distribution that minimizes the harm incurred by attackers is supported on a discrete set. This allows the defender team to allocate resources to a few types and yet tackle a large number of attacker types. We study this model in different settings to characterize a set of guiding principles for control problems with heterogeneous teams of agents, e.g., sensitivity of the harm to sub-optimal defender distributions, teams consisting of a small number of attackers and defenders, estimating and tackling an evolving attacker distribution, and competition between defenders that gives near-optimal behavior using decentralized computation of the control. We also compare this model with reinforcement-learned policies for the defender team.