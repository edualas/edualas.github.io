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
* M.Sc. in Integrated Climate System Sciences (ICSS), 2019-2022
* B.Sc. in Physics (Theoretical Physics Track), Complutense University of Madrid, 2014-2019
  * Erasmus exchange (Courses of MSc Theoretical Physics and MSc Science for Energy and Sustainability), University of Amsterdam, 2017-2018

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
