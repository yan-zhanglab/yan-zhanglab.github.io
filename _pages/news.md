---
layout: archive
title: "News"
permalink: /news/
author_profile: false
---

{% include base_path %}

<style>
.news-list {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin: 1.5rem 0;
}
.news-item {
  padding: 1rem 1.2rem;
  border: 1px solid #d8dee6;
  border-left: 3px solid #1a2b4c;
  border-radius: 8px;
  background: #fff;
  transition: box-shadow 0.2s ease, border-color 0.2s ease;
}
.news-item:hover {
  box-shadow: 0 4px 12px rgba(26,43,76,0.12);
  border-left-color: #3d6fb4;
}
.news-date {
  font-size: 0.8rem;
  color: #6b7280;
  margin-bottom: 0.3rem;
}
.news-title {
  font-weight: 600;
  font-size: 1.02rem;
  color: #1a2b4c;
  line-height: 1.35;
  margin-bottom: 0.4rem;
}
.news-title a {
  color: inherit;
  text-decoration: none;
}
.news-title a:hover {
  text-decoration: underline;
}
.news-body {
  font-size: 0.92rem;
  color: #444;
  line-height: 1.6;
}
.news-body p:last-child {
  margin-bottom: 0;
}
</style>

{% assign items = site.news | sort: "date" | reverse %}

<div class="news-list">
{% for item in items %}
  <div class="news-item">
    <div class="news-date">{{ item.date | date: "%B %-d, %Y" }}</div>
    <div class="news-title">{% if item.link %}<a href="{{ item.link }}">{{ item.title }}</a>{% else %}{{ item.title }}{% endif %}</div>
    <div class="news-body">{{ item.content | markdownify }}</div>
  </div>
{% endfor %}
</div>
