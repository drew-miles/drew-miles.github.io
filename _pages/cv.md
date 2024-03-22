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
* Ph.D in Astronomy & Astrophysics, Penn State University, 2021
* M.S. in Astronomy & Astrophysics, Penn State University, 2018
* B.S. in Physics and Astronomy, The University of Iowa, 2015

Academic Positions Held
======
* Research Assistant Professor, Caltech 2024 - Present
* Postdoc, Caltech 2022 - 2024
* Graduate Fellow, Penn State University, 2016 - 2021
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
