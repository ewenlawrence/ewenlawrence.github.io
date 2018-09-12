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

<p>When a quantum system is strongly coupled to its environment the usual approximations used to derive a master equation break down, and we need to use more sophisticated methods. 
These non-Markovian systems are particularly relevant for understanding the mechanisms of decoherence in solid state systems. 
We have developed new methods combining the path integral description of quantum mechanics with matrix product based techniques to numerically find the dynamics of these open quantum systems.</p>

<p>Recent publications about non-Markovian systems are below:</p>

{% for post in site.preprints reversed %}
  {% if post.project == 'non-Markovian' %}
    {% include archive-short.html %}
  {% endif %}
{% endfor %}

{% for post in site.publications reversed %}
  {% if post.project == 'non-Markovian' %}
    {% include archive-short.html %}
  {% endif %}
{% endfor %}

<br />

</div>

## The Open Dicke Model

<div style="max-width: 750px;">

<img src="{{ 'Dicke1.png' | prepend: "/images/" | prepend: base_path }}" width="700"> 

<p>The Dicke model provides a simple fully quantum mechanical description of the interaction between light confined in a cavity and matter. 
It predicts a phase transition between a state where the cavity is empty and a superradiant phase where the cavity mode is macroscopically occupied.
However, experimental realisations of this model are all in non-equilibrium situations where driving and dissipation are important.
We have been involved in developing techniques to understand the fate of this phase transition in the presence of various non-equilibrium effects.</p>

<p>Recent publications about the Dicke model are below:</p>

{% for post in site.preprints reversed %}
  {% if post.project == 'Dicke model' %}
    {% include archive-short.html %}
  {% endif %}
{% endfor %}

{% for post in site.publications reversed %}
  {% if post.project == 'Dicke model' %}
    {% include archive-short.html %}
  {% endif %}
{% endfor %}

<br />

</div>

## Organic Polaritons

<div style="max-width: 750px;">

<img src="{{ 'organic1.png' | prepend: "/images/" | prepend: base_path }}" width="700"> 

<p>Polaritons are quasiparticles made by hybridising electronic excitations with photons in a cavity. 
Typically the electronic excitation is bound electron-hole pair in a quantum well.
Recently it has become possible to instead use an electronic transition of a large organic molecule. 
These molecules typically have much larger dipole moments and so polariton physics can be seen at room temperature.
However, there are typically more degrees of freedom of the molecule to worry about. 
We focus on understanding the effects of these degrees of freedom such as vibrational and rotational motion of the molecules on the polariton physics.</p>

<p>Recent publications about organic polaritons are below:</p>

{% for post in site.preprints reversed %}
  {% if post.project == 'organic polaritons' %}
    {% include archive-short.html %}
  {% endif %}
{% endfor %}

{% for post in site.publications reversed %}
  {% if post.project == 'organic polaritons' %}
    {% include archive-short.html %}
  {% endif %}
{% endfor %}

<br />

</div>

## Photon BEC

<div style="max-width: 750px;">

<img src="{{ 'photonBEC1.png' | prepend: "/images/" | prepend: base_path }}" width="700"> 

<p>Recent experiments have observed the Bose-Einstein condensation of photons. 
Confining the light in a multimode cavity along with a small amount of fluorescent dye allows it to thermalise to the temperature of the dye, undergoing a transition to a BEC above a critical pump strength.
We have been involved with developing a microscopic model of this process allowing us to understand the thermalisation process in detail along with being able to predict many details of the experiments.</p>

<p>Recent publications about photon BEC are below:</p>

{% for post in site.preprints reversed %}
  {% if post.project == 'photonBEC' %}
    {% include archive-short.html %}
  {% endif %}
{% endfor %}

{% for post in site.publications reversed %}
  {% if post.project == 'photonBEC' %}
    {% include archive-short.html %}
  {% endif %}
{% endfor %}

</div>
