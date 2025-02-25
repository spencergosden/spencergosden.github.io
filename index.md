---
layout: default
title: "Home"
---


<img src="assets/266746399_GOSDEN SPENCER.jpeg" width="210">

# Welcome to my website! I am Spencer Gosden.
I am an undergraduate Finance student at the Georgia Institute of Technology.

* __Email__: [spencergosden@gatech.edu](mailto:spencergosden@gatech.edu)


{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
