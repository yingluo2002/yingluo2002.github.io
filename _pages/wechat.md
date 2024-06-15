---
layout: archive
title: "Wechat Posts"
permalink: /wechat/
author_profile: true
---

{% include base_path %}

{% for post in site.wechat %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}

