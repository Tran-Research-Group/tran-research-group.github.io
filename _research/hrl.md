---
title: "Hierarchical RL"
excerpt: "We work on hierarchical learning for autonomous agents."
header:
    teaser: /assets/images/hrl.png
tags:
  - hierarchical RL
  - successor features
---

We work on hierarchical reinforcement learning (RL) methods to create autonomous agents that can efficiently solve complex tasks.

## Bioinspired discovery of hierarchical subtasks

<figure-full-caption>
	<a href="{{ site.url }}{{ site.baseurl }}/assets/images/snac.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/snac.png"></a>
	<figcaption>Value maps for two learned sub-policies. The object-based option is learned using features specialized to focus on dynamic objects - it appears to have the blue agent prevent the enemy agent (E) from reaching the blue flag (blue star). The spatial-based option is learning using spatial features and is independent of the enemy.</figcaption>
</figure-full-caption>

Inspired by recent discoveries in neuroscience, this work explores the use of **feature specialization and clustering** to decompose environments into a useful task subspace for hierarchical RL. See our ALA Workshop [paper]({% post_url 2022-03-12-aamas-snac %}) presenting our approach, named **Specialized Neurons and Clustering (SNAC)**, for more details.

<!-- <div class="row">
    <a href="https://doi.org/10.48550/arXiv.2202.07741" class="button_general">arXiv</a>
    <a href="#" class="button_general">GitHub</a>
</div> -->

## Adaptation in hierarchical RL

<video muted autoplay="autoplay" loop="loop" width="50%" controls>
  <source src="/assets/videos/hrl.mp4" type="video/mp4">
</video>

This work explores the benefits of using hierarchical architectures in RL for **adaptation to new dynamics**. The video shows an example of how our approach supports fast adaptation to new enemies in a game of capture-the-flag. See our ICRA for more details.

<div class="row">
    <a href="https://doi.org/10.1109/ICRA40945.2020.9197052" class="button_general">DOI</a>
    <!-- <a href="https://github.com/raide-project/ctf_public" class="button_general">GitHub</a> -->
    <a href="https://youtu.be/BijWGu9xIpU" class="button_general">YouTube (short)</a>
    <a href="https://youtu.be/xzJLUpFknbQ" class="button_general">YouTube (long)</a>
</div>