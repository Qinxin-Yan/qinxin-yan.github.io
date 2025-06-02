---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Program of Applied and Computational Mathematics(PACM), Mathematics Department, Princeton University, 2021-2026(expected).
* Visiting Scholar at Insurance Mathematics and Stochastic Finance, Department of Mathematics, ETH Zurich, 2023-2024.
* B.S. in Computational Mathematics,  University of Science and Technology of China, 2017-2021.


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
