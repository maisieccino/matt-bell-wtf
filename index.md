---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: ""
navigation: true
---

# matt bell

I'm building platforms at State Street Corporation.

This site is still a bit work in progress, so bear with for a little bit.

## past and present work

{% assign projects = site.projects | sort: "date", "first" | reverse %}
{% for p in projects limit: 4%}
{% include project.html p=p %}
{% endfor %}

Contact

[Twitter: @mbellgb](https://twitter.com/mbellgb)

[GitHub: @mbellgb](https://github.com/mbellgb)