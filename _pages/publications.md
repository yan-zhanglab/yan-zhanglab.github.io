---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

The complete list of publications can also be found on [Google Scholar](https://scholar.google.com/citations?user=nmgE5hkAAAAJ&hl=en).

<div class="publication-grid">
  {% assign publications = site.publications | sort: "date" | reverse %}

  {% for post in publications %}
    {% include publication-card.html %}
  {% endfor %}
</div>