---
layout: archive
title: "Members"
permalink: /members/
author_profile: true
---

{% include base_path %}

{% for post in site.members %}
  {% if post.role == "Group leader" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %} 

{% for post in site.members %}
  {% if post.role == "PhD student" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %} 