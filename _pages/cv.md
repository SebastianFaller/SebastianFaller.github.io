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
* Ph.D in Cryptography, IBM Research Zurich and ETH Zurich, Supervisors: Dr. Julia Hesse, Prof. Dr. Dennis Hofheinz, 2026 (expected)
* M.S. in Computer Science, Karlsruhe Institute of Technology, 2022
* B.S. in Computer Science, Karlsruhe Institute of Technology, 2019


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
