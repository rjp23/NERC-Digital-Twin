---
title: Team
layout: single
permalink: /team/
collection: team
---

{% for team in site.team %}
- {{ team.name }}
{% endfor %}
