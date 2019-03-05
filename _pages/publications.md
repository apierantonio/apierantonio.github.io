---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Multi-view approaches for software and system modelling: a systematic literature review
Software and Systems Modeling
2019 | journal-article
DOI: 10.1007/s10270-018-00713-wEID: 2-s2.0-85061733132

Quality-Driven Detection and Resolution of Metamodel Smells
IEEE Access
2019 | journal-article
DOI: 10.1109/ACCESS.2019.2891357EID: 2-s2.0-85061749093
