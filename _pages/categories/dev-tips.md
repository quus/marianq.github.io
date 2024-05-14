---
title: "개발 관련 단순 Tips"
layout: archive
permalink: categories/dev-tips
author_profile: true
types: posts
---

{% assign posts = site.categories['dev-tips']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
