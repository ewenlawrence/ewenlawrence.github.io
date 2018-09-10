---
layout: archive
title: "Publications and Preprints"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>


{% include base_path %}


<img src="{{ cloud-peter-kirton.png | prepend: "/images/" | prepend: base_path }}"> 

## Preprints

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

## Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
