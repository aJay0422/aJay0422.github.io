---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

{% include base_path %}

Here are some notes I took during learning.

{% assign post = site.blogs | where: "path", "blog1.md" %}
{% include archive-single.html %}

{% assign post = site.blogs | where: "path", "blog2.md" %}
{% include archive-single.html %}