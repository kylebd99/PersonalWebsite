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
* B.S. in Statistics and Computer Science, Harvard University, 2020
* Ph.D in Computer Science, University of Washington, 2026 (expected)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching and Mentoring
======
* Taught CS 599K "The Theory and Practice of Tractable Programming"
  * This class went through the core theory and systems principles underlying tractable programming languages like SQL, einsum, etc.. 

Industry experience
======
* Summer 2023: Research Intern at RelationalAI
  * Implemented the Degree Sequence Bound in the query optimizer of a production database system.
* Fall 2021: Database Consultant at The Energy Authority
  * Performed an evaluation of database technologies and existing data flows for a non-profit which consults for municipal and county-owned electrical utilities.
* Summer 2020: Research Intern at Microsoft Research
  * Adapted learned indexing techniques to handle string data.
* Summer 2018, 2019: Software Engineering Intern at Google
  * Implemented data engineering pipelines to support search for hotel and vacation rental listing 
