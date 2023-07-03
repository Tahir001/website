---
layout: archive
title: "AI Notes"
permalink: /AInotes/
location: "Toronto, Canada"
---

The following page contains some of the knowledge I've gained about AI and ML throughout my years. Hoping to grow this over the next few years, as I climb the ladder & immerse myself in more AI related work. 

# AI Course Notes


<div class="course">
  <div class="course-image">
    <img src="ML_course.jpeg" alt="Course 1 Image">
  </div>
  <div class="course-info">
    <h2>Course 1: Introduction to Artificial Intelligence</h2>
    <a href="course1_notes.md">Course 1 Notes</a>
  </div>
</div>

<div class="course">
  <div class="course-info">
    <h2>Course 2: Machine Learning Fundamentals</h2>
    <a href="course2_notes.md">Course 2 Notes</a>
  </div>
  <div class="course-image">
    <img src="course2_image.jpg" alt="Course 2 Image">
  </div>
</div>

<!-- Repeat the above pattern for the remaining courses -->

<style>
.course {
  display: flex;
  flex-direction: row;
  margin-bottom: 30px;
}

.course-info {
  flex: 1;
  padding: 20px;
  background-color: #f5f5f5;
}

.course-image {
  flex: 1;
  display: flex;
  align-items: center;
  justify-content: center;
}

.course-image img {
  max-width: 100%;
  max-height: 200px;
}
</style>

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