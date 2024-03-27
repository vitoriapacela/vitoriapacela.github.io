---
layout: archive
title: "Presentations"
permalink: /talks/
author_profile: true
---

Talks
=====
**Análise de Componentes Independentes para Dados Binários**
- Instituto de Matemática Pura e Aplicada (IMPA), Seminário Centro Pi. January 2023, Rio de Janeiro, Brazil. [Video](https://www.youtube.com/watch?v=L4PvFaKs_eE&list=PLo4jXE-LdDTQ0Ujvto1jy-XjOKW4Ozs2h)
- FGV EMAp – Escola de Matemática Aplicada, Seminar. January 2023, Rio de Janeiro, Brazil.


Poster Presentations
=====

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
