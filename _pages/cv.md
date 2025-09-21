---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
[📄 CV.pdf](/files/250919-CV-JinLi.pdf){:target="_blank" download="CV_JL.pdf"}

Education
======
* Ph.D in Beijing/China, Institute of Atmospheric Physics, Chinese Academy of Sciences, 2021-Now (in progress)
* B.S. in Nanjing/China, Nanjing University of Information Science and Technology, 2017-2021
  
Skills
======
* Strong self-learning ability and skilled in hands-on tasks
* Proficient in programming with Python and Fortran for scientific computing and data analysis
* Numerical Modeling & Simulation


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
  
{% comment %}
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
{% endcomment %}