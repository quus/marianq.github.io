---
title: "개발 관련 단순 Tips"
layout: archive
permalink: categories/simple_tips
author_profile: true
types: posts
---

{% assign posts = site.categories['simple_tips']%}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
