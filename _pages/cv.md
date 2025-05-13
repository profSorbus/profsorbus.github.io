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
* Master in Evaluation and Public Decision, Computer Science Specility, ENSAI, 2022
* DAFFE : French chess diploma to teach chess by the chess federation

Work experience
======
* 2020 - 2022 : Civil servant at INSEE
  * French national statistical institute

* 2022 - Today : Data ingeneer
  * Centre d'accès sécurisé aux données (CASD secure data hub)
  * Duties included: Assisting researchers / Developing intern projects
  * Supervisor: Eric Debonnel / Kamel Gadouche

* Summer 2019 : Chess teacher
  * Teaching chess in holyday center in the south of France
  * Specialisation in the developement of handicap and chess
  
Skills
======
* Software developement : DB, Buisness layer, API (Web or CLI), not the greatest at frontend, but it's never too late to learn !
* Data processing with Spark, Python, R ...
* Data storage (Parquet, SQL)

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
