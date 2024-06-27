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
* Ph.D in Department of Systems Engineering, City University of Hong Kong, 2027 (expected)
* M.S. in Department of Transportation Engineering, Shandong University, 2023
* B.S. in Department of Civil Engineering, Shandong University, 2020

Skills
======
* Python, PyTorch, Matlab
* LaTeX, MicroSoft Office, Origin, TikZ
* Endnote, Zotero

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
* N/A
