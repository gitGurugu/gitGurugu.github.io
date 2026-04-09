---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am currently pursuing a master degree in computer science at Southeast University.

My research interests include multimodal large language models and large language models.

The achievements and experiences listed below are organized by category. Click a section in the navigation bar to jump directly to it.

## Recent Blog Posts
{% assign recent_posts = site.posts | slice: 0, 3 %}
{% for post in recent_posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) · {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
- [查看全部]({{ "/blog/" | relative_url }})
