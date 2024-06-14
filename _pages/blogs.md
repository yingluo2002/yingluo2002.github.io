---
layout: archive
title: "Blogs"
permalink: /blogs/
author_profile: true
---

{% include base_path %}

{% for post in site.blogs %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}

