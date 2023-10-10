---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Technical reports

## 2023
<u>Vitória Barin-Pacela</u>, Kartik Ahuja, Simon Lacoste-Julien, Pascal Vincent. **Identifiability of Discretized Latent Coordinate Systems via Density Landmarks Detection**. arXiv:2306.16334 [CS.LG], June 2023. [Paper](https://arxiv.org/abs/2306.16334).

## Published papers
## 2022

A. Hyttinen, <u>V. Barin-Pacela</u>, A. Hyvärinen. **Binary Independent Component Analysis: A Non-stationarity-based Approach**. <i>38th Conference on Uncertainty in Artificial Intelligence (UAI)</i>. 2022. [Paper](https://proceedings.mlr.press/v180/hyttinen22a.html).

___

## 2020

D. Belayneh, F. Carminati, A. Farbin, B. Hooberman, G. Khattak, M. Liu, J. Liu, D. Olivito, <u>V. Barin Pacela</u>, M. Pierini, A. Schwing, M. Spiropulu, S. Vallecorsa, J-R. Vlimant, W. Wei, and M. Zhang. **Calorimetry with deep learning: particle simulation and reconstruction for collider physics**. <i>The European Physical Journal C</i>. 80 (7), 1-31. 2020. [Paper](https://link.springer.com/article/10.1140/epjc/s10052-020-8251-9)


___

## 2017

B. Hooberman, M. Zhang, W. Wei, <u>V. Barin Pacela</u>, G. Khattak, S. Vallecorsa, A. Farbin, J-R. Vlimant, F. Carminati, M. Spiropulu, M. Pierini. **Calorimetry with deep learning: particle classification, energy regression, and simulation for high-energy physics**. <i>Workshop on Deep Learning for Physical Sciences, NIPS</i>. 2017. [Paper](https://dl4physicalsciences.github.io/files/nips_dlps_2017_15.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
