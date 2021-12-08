---
title: Team
layout: collection
permalink: /team/
collection: team
entries_layout: grid
classes: wide
---

{% for team_member in site.team %}
  <h2>{{ team_member.name }} - {{ team_member.role }}</h2>
  <p>{{ team_member.institute }}</p>
{% endfor %}
