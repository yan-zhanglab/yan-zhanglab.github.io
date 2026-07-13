---
layout: archive
title: "Members"
permalink: /members/
author_profile: false
---

{% assign current_members = site.members
  | where: "status", "current"
  | sort: "order" %}

<div class="member-grid">
  {% for member in current_members %}
    {% include member-card.html member=member %}
  {% endfor %}
</div>

{% assign alumni = site.members
  | where: "status", "alumni"
  | sort: "order" %}

{% if alumni.size > 0 %}
<h2>Alumni</h2>

<div class="member-grid">
  {% for member in alumni %}
    {% include member-card.html member=member %}
  {% endfor %}
</div>
{% endif %}