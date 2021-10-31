---
layout: archive
title: "Blog posts"
permalink: /year-archive/
author_profile: true
classes: wide
---

{% include base_path %}

{% for post in site.posts reversed %}
  {% include archive-single.html %}
{% endfor %}

------------
