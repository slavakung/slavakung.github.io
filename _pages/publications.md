---
layout: archive
title: "Some Featured Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Please see my [Google Scholar profile](https://scholar.google.cz/citations?user=ovfDEVwAAAAJ&hl=cs) for a full list of my publications.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}