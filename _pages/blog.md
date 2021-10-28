---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
classes: wide
---

{% include base_path %}

{% for post in site.blogs reversed %}
  {% include archive-single.html %}
{% endfor %}

------------
