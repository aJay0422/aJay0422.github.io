---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

{% include base_path %}

Here are some notes I took during learning. aaaa


{% assign blogs = site.pages | where: "path", "blogs/blog1.md" %}
{% assign blogs = blogs | concat: site.pages | where: "path", "blogs/blog2.md" %}

{% for blog in blogs %}
  {% include archive-single.html %}
{% endfor %}


<!-- {% assign post = site.blogs | where: "path", "blog1.md" %}
{% include archive-single.html %}

{% assign post = site.blogs | where: "path", "blog2.md" %}
{% include archive-single.html %} -->
