---
layout: archive
title: "Posts"
permalink: /posts/
author_profile: true
---

Here are some notes I took during learning.

{% for post in site.posts reversed %}
  {% include archive-single.html %}
{% endfor %}