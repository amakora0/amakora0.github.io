---
layout: archive
title: "Publications" 
permalink: /publications/
author_profile: true
---

**Improved Approximations for Relative Survivable Network Design**\
with Michael Dinitz, Guy Kortsarz, and Zeev Nutov\
_Workshop on Approximation and Online Algorithms (WAOA), 2023_\
[arXiv](https://arxiv.org/abs/2304.06656)

**Relative Survivable Network Design**\
with Michael Dinitz and Guy Kortsarz\
_International Conference on Approximation Algorithms for Combinatorial Optimization Problems (APPROX), 2022_\
[arXiv](https://arxiv.org/abs/2206.12245)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
