---
layout: archive
title: "Community work"
permalink: /teaching/
author_profile: true
---

{% include base_path %}


## Teaching ##

past & present courses:

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
