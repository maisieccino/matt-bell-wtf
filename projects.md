---
layout: page
title: Projects
navigation: true
---

{% assign projects = site.projects | sort: "date", "first" | reverse %}
{% for p in projects %}
{% include project.html p=p %}
{% endfor %}