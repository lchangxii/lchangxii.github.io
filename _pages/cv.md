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

Work experience
======
* Reserch Fellow, (To start)
  * National University of Singapore
* Senior Software Engineer, Mar. 2020 - Aug. 2020
  * Huawei

  
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
  {% assign reversed_pubs = site.publications | reverse %}
  <ul>{% for post in reversed_pubs %}
    {% assign index = forloop.index%}
    {% include archive-single.html %}
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



<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
