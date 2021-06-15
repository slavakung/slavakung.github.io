---
layout: archive
title: "Featured Projects"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

These are my featured academic projects. You can also check my [Github Account](https://github.com/GustikS) for some related software repositories.

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

