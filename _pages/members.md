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
    <article class="member-profile">

      {% if member.image %}
        <img
          class="member-profile__image{% if member.image_fit == 'contain' %} member-profile__image--contain{% endif %}"
          src="{{ member.image | relative_url }}"
          alt="{{ member.title }}"
        >
      {% endif %}

      <div class="member-profile__content">
        <h2 class="member-profile__name">{{ member.title }}</h2>

        {% if member.position %}
          <p class="member-profile__position">{{ member.position }}</p>
        {% endif %}

        {% if member.expertise %}
          <p>
            <span class="member-profile__label">Expertise:</span>
            {{ member.expertise }}
          </p>
        {% endif %}

        {% if member.excerpt %}
          <div class="member-profile__bio">
            {{ member.excerpt | markdownify }}
          </div>
        {% endif %}

        {% if member.education %}
          <div class="member-profile__education">
            {{ member.education | markdownify }}
          </div>
        {% endif %}

        {% if member.office %}
          <p>Office: {{ member.office }}</p>
        {% endif %}

        {% if member.email %}
          <p>
            <a href="mailto:{{ member.email }}">{{ member.email }}</a>
          </p>
        {% endif %}
      </div>

    </article>
  {% endfor %}
</div>