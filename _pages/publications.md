---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## 2024
<u>Vitória Barin-Pacela</u>, Kartik Ahuja, Simon Lacoste-Julien, Pascal Vincent. *On the Identifiability of Quantized Factors*. **3rd Conference on Causal Learning and Reasoning ([CLeaR](https://www.cclear.cc/2024))**. [[Paper]](https://arxiv.org/abs/2306.16334) [[Code]](https://github.com/facebookresearch/quantized_identifiability)

## 2022

Antti Hyttinen, <u>Vitória Barin-Pacela</u>, Aapo Hyvärinen. *Binary Independent Component Analysis: A Non-stationarity-based Approach*. **38th Conference on Uncertainty in Artificial Intelligence (UAI)**. 2022. [[Paper]](https://proceedings.mlr.press/v180/hyttinen22a.html)

___

## 2020

D. Belayneh, F. Carminati, A. Farbin, B. Hooberman, G. Khattak, M. Liu, J. Liu, D. Olivito, <u>V. Barin Pacela</u>, M. Pierini, A. Schwing, M. Spiropulu, S. Vallecorsa, J-R. Vlimant, W. Wei, and M. Zhang. *Calorimetry with deep learning: particle simulation and reconstruction for collider physics*. **The European Physical Journal C**. 80 (7), 1-31. 2020. [[Paper]](https://link.springer.com/article/10.1140/epjc/s10052-020-8251-9)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
