---
title: "Intelligent Transportation Systems"
excerpt: "We work on algorithms for intelligent transportation systems."
header:
    teaser: /assets/images/its.jpeg
tags:
  - intelligent transportation systems
  - reinforcement learning
last_modified_at: 2023-08-28
---

We work on artificial intelligence and machine learning methods to improve autonomy and traffic management in intelligent transportation systems (ITS).

<!-- ## MARL for traffic light control

This work explores applications of MARL to traffic light control. We are specifically exploring the integration of hierarchical RL with MARL for this problem. We use SUMO as the traffic simulator. -->

## Learning emergent coordination in collective autonomous air mobility systems (CAMS)

This work explores reinforcement learning algorithms for encouraging emergent cooperation in autonomous air mobility vehicles, with consideration of heterogeneity (e.g., individual objectives) and the overall integrated system (e.g., vehicles and their interactiosn with operators and services).

## Evaluating STGNNs for air transportation networks

<figure-full-caption>
	<a href="{{ site.url }}{{ site.baseurl }}/assets/images/us-atn.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/us-atn.png"></a>
	<figcaption>Visualization of the US air transportation network studied in our work.</figcaption>
</figure-full-caption>

This work builds upon our earlier work using [STGNNs for railway networks](#predicting-delays-in-railway-networks) by exploring potential benefits of STGNNs with **various graph convolution operations** towards delay prediction in air transportation networks.

## Predicting delays in railway networks

<figure class="half">
    <a href="{{ site.url }}{{ site.baseurl }}/assets/images/railway-gnn.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/railway-gnn.png" style="width:500px"></a>
    <a href="{{ site.url }}{{ site.baseurl }}/assets/images/railway-gnn.png"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/railway-network.png" style="width:500px"></a>
    <figcaption>Notional view of an STGNN architecture and the portion of the British railway network studied in our work.</figcaption>
</figure>

This work leverages **spatio-temporal graph neural networks (STGNNs)** to predict delays in railway networks. We find that STGNNs improve predication accuracy relative to linear and vanilla multi-layer perceptron models. See our ITSC paper presenting our results for more details.

<div class="row">
    <a href="https://doi.org/10.1109/ITSC45102.2020.9294742" class="button_general">DOI</a>
    <a href="https://github.com/Tran-Research-Group/raildelays-public" class="button_general">GitHub</a>
    <a href="https://youtu.be/p5LO97n3llg" class="button_general">YouTube</a>
</div>