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
* Ph.D in Computer Science, Universidade Estadual de Campinas (UNICAMP), 2026 (expected)
* M.S. in Computer Science, Universidade Estadual de Campinas (UNICAMP), 2022
* B.S. in Computer Science, Universidade Estadual de Maringá (UEM), 2019

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching Internship
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  