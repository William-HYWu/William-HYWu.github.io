---
layout: archive
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* BSE in Computer Science, University of Michigan, 2027 **(Expected)**
* BE in Mechanical Engineering, Shanghai Jiao Tong Unversity, 2027 **(GPA: 3.97/4.0, Ranking: 1/336)**

Research/Internship
======
* [SIRIUS Lab](https://banyutong.github.io/sirius_lab_website/index.html#research) (Advisor: Prof. Yutong Ban)
  
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
