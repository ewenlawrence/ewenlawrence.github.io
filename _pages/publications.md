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

<H1>Preprints</H1>

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

<H1>Publications</H1>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
