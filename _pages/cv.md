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
* Ph.D in National University of Singapore, Aug. 2021 - Sep. 2025
* M.S. in Beihang University, Sep. 2017 - Jan. 2020
* B.S. in Beihang University, Sep. 2013 - Jun. 2017

Acadamic Work experience
======
* Reserch Fellow, Nov. 2025 - May. 2026
  * National University of Singapore 


  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
  <ul>{% assign index = 1 %}{% for i in (0..999) reversed %}
    {% assign i_str = i | append: "" %}
    {% for post in site.publications %}
    {% assign post_number = post.path | split: "/" | last | split: "." | first %}
    {% if post_number != i_str %}
    {% continue %}
    {% endif %}
    {% include archive-single.html %}
    {% assign index = index | plus: 1 %}
    {% endfor %}
  {% endfor %}</ul>
  <ul>*Authors with equal contribution.</ul>

Award
======
* Travel Grant (ISCA 2025, MICRO 2023, ISCA 2022)
* Research Achievement Award, National University of Singapore (2023)
* Excellent Graduate, Beihang University (2020)
* National Scholarship, China (2018)
* Annual ISC-HPCAC Student Cluster Competition (ISC 2017): Bronze Prize
* Asia Student Supercomputer Challenge (ASC 2017): Silver Prize (team leader)

<!--* [Annual ISC-HPCAC Student Cluster Competition (ISC 2017): Bronze Prize](https://www.hpcadvisorycouncil.com/events/2017/isc17-student-cluster-competition/)
* [Asia Student Supercomputer Challenge (ASC 2017): Silver Prize](https://www.hpcwire.com/2017/05/01/asc17-tsinghua-team-crowned-champion-beihang-runner/) as the team leader-->

<!-- -- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single.html %}
  {% endfor %}</ul>


Service
======

### Program Committee
- **IEEE/ACM International Symposium on Microarchitecture (MICRO)** — 2026  
- **International Symposium on Computer Architecture (ISCA)** — 2026  
- [**GPGPU 2026**](https://mocalabucm.github.io/gpgpu2026/) — 2026  
- [**3rd Workshop on Computer Architecture Modeling and Simulation (CAMS)**](https://sarchlab.org/cams25) — 2025  
- [**2nd Workshop on Computer Architecture Modeling and Simulation (CAMS)**](https://sarchlab.org/cams24) — 2024  

### Journal Reviewer
- *IEEE Transactions on Computers (TC)*
- *ACM Transactions on Architecture and Code Optimization (TACO)* 
- *The Journal of Supercomputing*

<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
