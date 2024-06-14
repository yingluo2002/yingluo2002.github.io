---
layout: archive
title: "Blogs"
permalink: /blogs/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.blogs reversed %}
  {% include archive-single.html %}
{% endfor %}
