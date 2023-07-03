---
layout: archive
title: "AI Notes"
permalink: /AInotes/
location: "Toronto, Canada"
---

The following page contains some of the knowledge I've gained about AI and ML throughout my years. Hoping to grow this over the next few years, as I climb the ladder & immerse myself in more AI related work. 

# AI Course Notes
<!DOCTYPE html>
<html>

<head>
  <title>AI Course Notes</title>
  <link rel="stylesheet" href="styles.css">
</head>

<body>
  <div class="container">
    <h1>AI Course Notes</h1>

    <div class="course">
      <div class="course-image">
        <img src="images/course_1_image.png" alt="Course 1 Image">
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
        <img src="images/course_2_image.png" alt="Course 2 Image">
      </div>
    </div>

    <!-- Repeat the above pattern for the remaining courses -->
  </div>
</body>

</html>


{% for post in site.AInotes reversed %}
  {% include archive-single.html %}
{% endfor %} 