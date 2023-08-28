---
title: ""
layout: splash
author_profile: false
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/drone.JPG
#   actions:
#     - label: "Download"
#       url: "https://github.com/mmistakes/minimal-mistakes/"
#   caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Advancing autonomy through interdisciplinary research."
intro: 
  - excerpt: "Welcome! Our goal is to advance research on autonomous and intelligent systems with a focus on autonomous robots that interact with each other and humans. We primarily work at the intersection of robotics, artificial intelligence, and multi-agent systems, though we draw inspiration from other fields, like neuroscience, as well."
  - excerpt: "Check out our [research](/research/) to learn more!"
---

{% include feature_row id="intro" type="center" %}

<!-- # Highlighted projects -->

# Latest news

<!-- <div class="feature__wrapper">
  {% for post in site.posts limit:3 %}
     {% include archive-single.html %}
  {% endfor %}
</div> -->

<div class="grid__wrapper">
  {% for post in site.posts limit:4 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

# Press

Our work has been highlighted at [UNITE.AI](https://www.unite.ai/ai-helps-train-teams-of-collaborative-robots-and-drones/).