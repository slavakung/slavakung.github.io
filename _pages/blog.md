---
title: "Blog"
permalink: /blog/
layout: archive
author_profile: true
---

Notes and essays on **science, mathematics, optimization, AI, innovation, and research practice**, together with accessible introductions to major new research and software results.

I use this section for material that sits between a research paper and a short announcement: the motivation behind a result, methodological or philosophical arguments, connections between projects, and occasional commentary on how mathematical ideas move into scientific and engineering practice.

{% assign posts = site.posts %}
{% if posts.size > 0 %}
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
_No posts yet._
{% endif %}

---

### Adding a new entry

Blog posts are ordinary Markdown files in the repository's `_posts/` directory. Copy `_drafts/blog-post-template.md`, rename it using

`YYYY-MM-DD-short-title.md`

and edit the title, date, excerpt, tags, and body. Commit/push it to GitHub and Jekyll will automatically add it to this page, newest first.
