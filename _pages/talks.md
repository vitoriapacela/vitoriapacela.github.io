---
layout: archive
title: "Poster presentations"
permalink: /talks/
author_profile: true
---

**Independent Component Analysis for Binary Data with Variational Autoencoders**
- Machine Learning Summer School (MLSS^N), Krakow (Poland), **2022**
- CIFAR Deep Learning + Reinforcement Learning (DLRL) Summer School, Canada (virtual), **2021**

___

**Fast Calorimeter Simulation with Wasserstein Generative Adversarial Networks**
- 14th Women in Machine Learning Workshop, Conference on Neural Information Processing Systems (NeurIPS), Vancouver (Canada), **2019**
- LatinX in AI Workshop, Conference on Neural Information Processing Systems (NeurIPS), Vancouver (Canada), **2019**

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
