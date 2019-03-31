---
layout: home
title: ""
navigation: true
---

# matt bell 🔔

I'm building platforms at State Street Corporation.

I also like the colour cyan.

This site is still a bit work in progress, so bear with for a little bit. 🔜
In the meantime, why not check out my [existing website](https://mbell.me)?

## past and present work

{% assign projects = site.projects | sort: "date", "first" | reverse %}
{% for p in projects limit: 4%}
{% include project.html p=p %}
{% endfor %}

[View all](/projects)