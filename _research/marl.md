---
title: "Multi-agent RL"
excerpt: "We work on learning for coordination of multi-agent systems."
header:
    teaser: /assets/images/dissc.png
tags:
  - artificial intelligence
  - multi-agent systems
  - reinforcement learning
---

We work on multi-agent reinforcement learning (MARL) methods to create teams of autonomous agents that can work together to solve challenging tasks, such as search-and-rescue, traffic control, autonomous driving, and warehouse robotics.

## Improving decentralized training with successor features

<video muted autoplay="autoplay" loop="loop" width="500px" controls>
  <source src="/assets/videos/dissc.mp4" type="video/mp4">
</video>

This work leverages successor features (SFs) to **disentangle** an individual agent’s impact on the global value function from that of all other agents, thus enabling better training of decentralized agents. The video shows an example of gameplay from the Starcraft Multi-Agent Challenge (SMAC) where the red agents learned to surround the blue agents and win the game, despite being at a numbers disadvantage (27 vs. 30 agents). See our AAMAS paper presenting our approach, named **DISentangling Successor features for Coordination (DISSC)**, for more details.

<div class="row">
    <a href="https://doi.org/10.48550/arXiv.2202.07741" class="button_general">arXiv</a>
    <!-- <a href="#" class="button_general">GitHub</a> -->
</div>

<!-- ## Learning multi-agent roles

This work builds from [DISSC](#improving-decentralized-training-with-successor-features) by leveraging SFs to learn **roles** that individual agents can use within a team, inspired by the use of different positions in team sports like football and basketball. Our preliminary results show **TODO**. -->

<!-- ## Leveraging communication through coordination graphs

This work aims to **TODO**. -->
