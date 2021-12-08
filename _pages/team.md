---
title: Team
layout: single
permalink: /team/
collection: team
entries_layout: grid
---

{% for team in site.team %}
- {{ team.name }}
{% endfor %}
