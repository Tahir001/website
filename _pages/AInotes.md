---
layout: archive
title: "AI Notes"
permalink: /AInotes/
location: "Toronto, Canada"
---

The following page contains some of the knowledge I've gained about AI and ML throughout my years. Hoping to grow this over the next few years, as I climb the ladder & immerse myself in more AI related work. 

# AI Course Notes

## Course 1: Introduction to Artificial Intelligence

![Course 1 Image](course1_image.jpg)

[**Course 1 Notes**](course1_notes.md)

---

## Course 2: Machine Learning Fundamentals

[**Course 2 Notes**](course2_notes.md)

![Course 2 Image](course2_image.jpg)

---

## Course 3: Deep Learning and Neural Networks

![Course 3 Image](course3_image.jpg)

[**Course 3 Notes**](course3_notes.md)

---

## Course 4: Natural Language Processing

[**Course 4 Notes**](course4_notes.md)

![Course 4 Image](course4_image.jpg)


{% for post in site.AInotes reversed %}
  {% include archive-single.html %}
{% endfor %} 