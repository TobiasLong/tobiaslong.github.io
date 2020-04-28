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
* BSc in Physics with Theoretical Physics, University of Nottingam, 2018
* MSc in Mathematical Medicine and Biology, University of Nottingham, 2019

Work experience
======
* Summer 2017: Research Assistant
  * Sir Peter Mansfield Imaging Centre - University of Nottingham
  * Project: Modelling SAR heating of the human head during UHF-MRI imaging
  * Supervisor: Professor Penny Gowland, Professor Paul Glover

* Summer 2018: Research Assistant
  * Condensed Matter Theory Group - University of Nottingham
  * Project: Deep Learning applied to the Ising Model
  * Supervisor: Professor Juan Garrahan
  
Skills
======
* Programming Experience: MATLAB, Python

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
