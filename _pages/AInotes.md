---
layout: archive
title: "AI Notes"
permalink: /AInotes/
location: "Toronto, Canada"
---

The following page contains some of the knowledge I've gained about AI and ML throughout my years. Hoping to grow this over the next few years, as I climb the ladder & immerse myself in more AI-related work. 

<style>
body {
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
  margin: 0;
  padding: 20px;
}

.container {
  max-width: 800px;
  margin: 0 auto;
}

h1 {
  text-align: center;
  margin-top: 40px;
  margin-bottom: 20px;
}

.course {
  display: flex;
  margin-bottom: 30px;
}

.course-title,
.course-image {
  flex: 1;
  padding: 20px;
  background-color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.course-title h2,
.course-title a {
  margin: 10px 0;
}

.course-image img {
  max-width: 100%;
  max-height: 200px;
}
</style>

<div class="container">
  <h1> </h1>

  <div class="course">
    <div class="course-title">
      <h2>Mathematical Foundations for Machine Learning and Data Science</h2>
      <a href="/_AInotes/MachineLearning.md">Course 1 Notes</a>
    </div>
    <div class="course-image">
      <img src="../images/Mathematics_for_ML.png" alt="Course 1 Image">
    </div>
  </div>

  <div class="course">
    <div class="course-image">
      <img src="../images/course_2_image.png" alt="Course 2 Image">
    </div>
    <div class="course-title">
      <h2> Machine Learning Algorithms </h2>
      <a href="../_AInotes/MachineLearning.md">Course 2 Notes</a>
    </div>
  </div>

  <div class="course">
    <div class="course-title">
      <h2> Computer Vision </h2>
      <a href="../_AInotes/NaturalLanguageProcessing.md">Course 3 Notes</a>
    </div>
    <div class="course-image">
      <img src="../images/Computer_Vision.png" alt="Course 3 Image">
    </div>
  </div>

  <div class="course">
    <div class="course-image">
      <img src="../images/Deep_Learning.png" alt="Course 4 Image">
    </div>
    <div class="course-title">
      <h2> Deep Learning Specialization </h2>
      <a href="../_AInotes/DeepLearning.md">Course 4 Notes</a>
    </div>
  </div>

  <div class="course">
    <div class="course-title">
      <h2> Natural Language Processing Specialization </h2>
      <a href="../_AInotes/NaturalLanguageProcessing.md">Course 5 Notes</a>
    </div>
    <div class="course-image">
      <img src="../images/NLP.png" alt="Course 5 Image">
    </div>
  </div>

  <div class="course">
    <div class="course-image">
      <img src="../images/ML_Production.png" alt="Course 6 Image">
    </div>
    <div class="course-title">
      <h2> Machine Learning in Production (MLOPs) Specialization </h2>
      <a href="course6_notes.md">Course 6 Notes</a>
    </div>
  </div>
</div>


{% for post in site.AInotes reversed %}
  {% include archive-single.html %}
{% endfor %} 