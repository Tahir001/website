---
layout: archive
title: "AI Notes"
permalink: /AInotes/
location: "Toronto, Canada"
---

The following page contains some of the knowledge I've gained about AI and ML throughout my years. Hoping to grow this over the next few years, as I climb the ladder & immerse myself in more AI related work. 


<!-- {% for post in site.AInotes reversed %}
  {% include archive-single.html %}
{% endfor %} -->

{% for category in site.AInotes %}
  ## {{ category.title }}
{% endfor %}