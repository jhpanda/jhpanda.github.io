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
* B.S. in Biology, University of Science and Technology of China, USTC, 2012
* Ph.D in Biochemistry and Molecular Biology, University of Science and Technology of China, USTC, 2017

Research experience
======
* 2019-present: Postdoctoral Researcher
  * Rockefeller University
  * Supervisor: Professor Li Zhao

* 2017-2019: Postdoctoral Researcher
  * Hong Kong University of Science and Technology
  * Supervisor: Professor Xuhui Huang
  
Skills
======
* Programming skills
  * Python
  * Bash
  * C

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
