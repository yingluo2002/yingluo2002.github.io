---
layout: archive
title: "CSDN Posts"
permalink: /csdn/
author_profile: true
---

{% include base_path %}

{% for post in site.csdn %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}

