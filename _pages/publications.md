---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## 2022

A. Hyttinen, <u>V. Barin-Pacela</u>, A. Hyvärinen. **Binary Independent Component Analysis via Non-stationarity**. <i>38th Conference on Uncertainty in Artificial Intelligence (UAI)</i>. 2022. [ArXiv](https://arxiv.org/abs/2111.15431).

___

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
