---
title: ""
layout: single
classes: wide_full
permalink: /research/
collection: research
# entries_layout: grid
---

Here are our ongoing projects. Past projects can be found in our [publications](/publications/) or Huy's [CV]({{ site.url }}{{ site.baseurl }}/assets/pdfs/huy-cv.pdf).

We gratefully acknowledge our funding sources.

<div class="funding-logos">
    <a href="https://www.arl.army.mil/"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/funding/arl.jpeg"></a>
    <a href="https://www.erdc.usace.army.mil/Locations/CERL/"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/funding/cerl.webp"></a>
    <a href="https://www.darpa.mil/"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/funding/darpa.png"></a>
    <a href="https://sustainability.illinois.edu/"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/funding/isee.png"></a>
    <a href="https://www.mitre.org/"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/funding/mitre.png"></a>
    <a href="https://www.nasa.gov/"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/funding/nasa.jpg"></a>
    <a href="https://www.onr.navy.mil/"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/funding/onr.png"></a>
    <a href="https://zjui.illinois.edu/"><img src="{{ site.url }}{{ site.baseurl }}/assets/images/funding/zjui.png"></a>
</div>

<archive class="grid__wrapper">
    {% for post in site.research %}
        {% include archive-single.html type="grid" %}
    {% endfor %}
</archive>