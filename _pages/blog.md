---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

{% for post in site.posts %}
  {% include archive-single.html type="list" %}
{% endfor %}
