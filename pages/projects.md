---
layout: page
title: Projects
---

{% for project in site.projects %}
  {% include project.html %}
{% endfor %}
