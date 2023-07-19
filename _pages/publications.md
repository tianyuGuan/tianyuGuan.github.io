---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Guan, T., Cao, J., and Swartz, T. (2023) Parking the Bus. Journal of Quantitative Analysis in Sports. Accepted.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
