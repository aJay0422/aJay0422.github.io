---
layout: archive
title: "Blog"
permalink: /blogs/
author_profile: true
---

{% include base_path %}

Here are some notes I took during learning. cccc


{% for blog in site.blogs %}
  {% include archive-single.html %}
{% endfor %}


<!-- {% assign post = site.blogs | where: "path", "blog1.md" %}
{% include archive-single.html %}

{% assign post = site.blogs | where: "path", "blog2.md" %}
{% include archive-single.html %} -->
