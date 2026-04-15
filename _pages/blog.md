---
title: "Blog"
layout: archive
permalink: /blog/
author_profile: false
---

{% assign posts = site.posts %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}
