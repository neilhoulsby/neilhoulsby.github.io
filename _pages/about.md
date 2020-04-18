---
permalink: /
title: "About"
excerpt: "Academic Webpage for Neil Houlsby"
author_profile: true
---

I am a Senior Research Scientist in the [Google Brain](https://research.google/teams/brain/) team.
I have broad in interests in machine learning and artificial intelligence, with a particular focusses on scalable methods, vision, language, and generalization.


Prior to joining Google, I received a PhD from the Cambridge [Computaqtional and Biological Learning lab](http://learning.eng.cam.ac.uk/Public/), supervised by Zoubin Ghahramani, and Máté Lengyel.
My areas of study were Bayesian ML, active learning, and cognitive science.


Publications
======

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
