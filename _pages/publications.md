---
layout: archive
title: "Publications and Preprints"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<H2>Preprints</H2>

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

<H2>Publications</H2>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
