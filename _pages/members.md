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
    <article class="member-card">

      {% if member.image %}
        <img
          class="member-card__image"
          src="{{ member.image | relative_url }}"
          alt="{{ member.title }}"
        >
      {% endif %}

      <div class="member-card__content">
        <h2 class="member-card__name">{{ member.title }}</h2>

        {% if member.position %}
          <p class="member-card__position">{{ member.position }}</p>
        {% endif %}

        {% if member.excerpt %}
          <p class="member-card__bio">{{ member.excerpt }}</p>
        {% endif %}
      </div>

    </article>
  {% endfor %}
</div>