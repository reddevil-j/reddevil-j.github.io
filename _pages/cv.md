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
* B.S. in Software Engineering, Isfahan University of Tech., 2009
* M.S. in Information Technology, Amirkabir University of Tech., 2013
* Ph.D in Computer Engineering, Boston University, 2023 (expected)

Work experience
======
* **Reserach Assistant**
  * Boston University
  * Duties included: Research on security of PHP application through integrated analysis of the PHP interpreter and web apps
  * Supervisor: Professor Manuel Egele

* **Research Assistant**
  * Amirkabir University of Tech.
  * Duties included: Designing multi-party computation protocols
  * Supervisor: Professor Babak Sadeghian
  
Skills
======
* Programming Languages
  * Python, C/C++, Go Lang, Java, PHP
* Vulnerability Detection
  * Fuzzing
  * Static/Dynamic taint analysis
  * Source-code Auditing
* Tools
  * Burp, Docker, Metasploit, SQLMap, Wireshark, gdb, Rabbitmq

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

  
Service and leadership
======
* Reviewer for IEEE Transactions on Emerging Topics in Computing (2020)
* Artifact reviewer for Annual Computer Security Applications Conference (2017, 2018)
