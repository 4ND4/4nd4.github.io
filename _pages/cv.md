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
* B.S.E. in Systems and Computing, Pontifical Catholic University of Ecuador, 2013
* M.S. in Computing and Security, King's College London, 2016
* Ph.D in Computer Science, University College Dublin, 2021

Work experience
======
* Feb 2017 - May 2021: Teaching Assistant
  * University College Dublin
  * Duties included: Supervision of postgraduate students, assignment corrections, exam invigilations.
  * Supervisor: Dr. Mark Scanlon
  
Skills
======
* Python
* Research
  * Plannification
  * Delivery
  * Quality
* Problem-Solving

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
