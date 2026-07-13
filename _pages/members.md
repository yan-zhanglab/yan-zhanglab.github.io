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
        <a
          class="member-card__image-link"
          href="{{ member.url | relative_url }}"
        >
          <img
            class="member-card__image{% if member.image_fit == 'contain' %} member-card__image--contain{% endif %}"
            src="{{ member.image | relative_url }}"
            alt="{{ member.title | escape }}"
          >
        </a>
      {% endif %}

      <div class="member-card__content">

        <h2 class="member-card__title">
          <a href="{{ member.url | relative_url }}">
            {{ member.title }}
          </a>
        </h2>

        {% if member.position %}
          <p class="member-card__position">
            {{ member.position }}
          </p>
        {% endif %}

        {% if member.excerpt %}
          <div class="member-card__summary">
            {{ member.excerpt | strip_html | truncatewords: 28 }}
          </div>
        {% endif %}

        <div class="member-card__links">
          <a href="{{ member.url | relative_url }}">
            Full Bio
          </a>

          {% if member.linkedin %}
            <a
              href="{{ member.linkedin }}"
              target="_blank"
              rel="noopener noreferrer"
            >
              LinkedIn
            </a>
          {% endif %}
        </div>

      </div>
    </article>
  {% endfor %}
</div>