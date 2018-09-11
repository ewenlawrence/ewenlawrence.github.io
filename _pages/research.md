---
layout: archive
title: "Research Interests"
permalink: /research/
author_profile: true
---


{% include base_path %}




## Non-Markovian Dynamics

<div style="max-width: 750px;">

<img src="{{ 'non-Markovian1.png' | prepend: "/images/" | prepend: base_path }}"> 

<p>When a quantum system is strongly coupled to it's environment the usual approximations used to derive a master equation break down, and we need to use more sophisticated methods. 
These non-Markovian systems are particularly relevant for understanding the mechanisms of decoherence in solid state systems. 
We have developed new methods combining the path integral description of quantum mechanics with matrix product based techniques to numerically find the dynamics of these open quatum systems.</p>

<p>Some recent publications about non-Markovian systems are below:</p>

{% for post in site.publications reversed %}
  {% if post.project == 'non-Markovian' %}
    {% include archive-short.html %}
  {% endif %}
{% endfor %}

</div>

## The Open Dicke Model

<div style="max-width: 750px;">

<img src="{{ 'Dicke1.png' | prepend: "/images/" | prepend: base_path }}" width="700"> 

The Dicke model provides a simple fully quantum mechical description of the interaction between light and matter. 

{% for post in site.publications reversed %}
  {% if post.project == 'Dicke model' %}
    {% include archive-short.html %}
  {% endif %}
{% endfor %}

</div>

## Organic Polaritons

<div style="max-width: 750px;">

<img src="{{ 'organic1.png' | prepend: "/images/" | prepend: base_path }}" width="700"> 

{% for post in site.publications reversed %}
  {% if post.project == 'organic polaritons' %}
    {% include archive-short.html %}
  {% endif %}
{% endfor %}

</div>

## Photon BEC

<div style="max-width: 750px;">

<img src="{{ 'photonBEC1.png' | prepend: "/images/" | prepend: base_path }}" width="700"> 

{% for post in site.publications reversed %}
  {% if post.project == 'photonBEC' %}
    {% include archive-short.html %}
  {% endif %}
{% endfor %}

</div>
