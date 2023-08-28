---
title: "Robotics and Autonomy"
excerpt: "We work on learning and control for robots and other autonomous systems."
header:
    teaser: /assets/images/lunar-lander.jpeg
tags:
  - controls
  - formal methods
  - reinforcement learning
last_modified_at: 2022-11-10
---

We work on artificial intelligence and controls methods for robots and other autonomous systems (e.g., for space and urban air mobility).

<!-- ## Fast adaptation for autonomous landers

This work explores the use of **model-based meta-RL** for the spacecraft powered descent guidance and control (PDG) problem. The system aims to be robust to potential uncertainties or new dynamics, for example due to engine failures or unexpected atmospheric conditions. -->

## Explaining autonomous agents

This work leverages **formal methods** to infer human-interpretable explanations of data-driven autonomous agents, such as those trained using deep reinforcement learning.

## Traversability for robot navigation in the field

<figure-full-caption>
	<a href="{{ site.url }}{{ site.baseurl }}/assets/images/WayFAST2.jpg"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/WayFAST2.jpg"></a>
	<figcaption>Our system predicts traversable paths for autonomous visual navigation in offroad terrain.</figcaption>
</figure-full-caption>

This work presents a new method for robot navigation in unstructured, outdoor environments based on self-supervised **traversability estimations**. See our RA-L paper presenting our approach, named **Waypoint Free Autonomous Systems for Traversability (WayFAST)**, for more details.

<div class="row">
    <a href="https://arxiv.org/pdf/2203.12071.pdf" class="button_general">PDF</a>
    <a href="https://doi.org/10.1109/LRA.2022.3193464" class="button_general">DOI</a>
</div>

## Anomaly detection

<figure-full-caption>
	<a href="{{ site.url }}{{ site.baseurl }}/assets/images/d-anogan.jpg"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/d-anogan.jpg"></a>
	<figcaption>Comparison of the disconnected latent space learned using our method (left) with the latent space learning using typical anomaly detection methods (right). We show that clustering in the latent space improves anomaly detection in multi-class datasets.</figcaption>
</figure-full-caption>

This work explores the problem of anomaly detection in disconnected data manifolds (i.e., multi-class anomaly detection) using a new combination of **multi-generator generative adversarial networks (GANs)** that leverages a learned bandit for clustering in the latent space. See our IJCNN 2022 paper presenting our approach, named **Disconnected Anomaly GAN (D-AnoGAN)**, for more details.

<div class="row">
    <a href="https://doi.org/10.1109/IJCNN55064.2022.9892270" class="button_general">DOI</a>
</div>