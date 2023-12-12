---
layout: archive
title: "Portfolio"
permalink: portfolio/
location: "Toronto, Canada"
---

The following page showcases some of my projects in the field of AI and ML.
<style>
    body {
        font-family: 'Arial', sans-serif;
        background-color: #f5f5f5;
        margin: 0;
        padding: 20px;
    }

    .container {
        max-width: 850px; /* Increase width by 50px */
        margin: 0 auto;
    }

    .project,
    .project2,
    .project3,
    .project4 {
        display: flex;
        align-items: center;
        margin-bottom: 15px; /* Decrease length by 5px */
        border: 1px solid #ddd;
        border-radius: 8px;
        padding: 10px;
        background-color: white;
    }

    .project-img {
        width: 70px; /* Increase width by 10px */
        height: 70px; /* Increase height by 10px */
        object-fit: cover;
        border-radius: 50%;
        margin-right: 10px;
    }

    .project-details {
        flex: 1;
    }

    .project-title {
        font-size: 17px; /* Increase font size by 1px */
        font-weight: bold;
        margin-bottom: 3px;
    }

    .project-authors {
        font-size: 13px; /* Increase font size by 1px */
        margin-bottom: 5px;
    }

    .project-conference {
        font-style: italic;
        font-size: 12px; /* Increase font size by 1px */
        margin-bottom: 5px;
    }

    .project-buttons {
        display: flex;
        margin-top: 5px;
        width: 50%; /* Buttons take up half the width */
    }

    .project-details a {
        flex: 1;
        display: inline-block;
        padding: 5px;
        margin-right: 5px;
        text-align: center;
        text-decoration: none;
        color: #fff;
        border-radius: 4px;
        cursor: pointer;
        transition: background-color 0.3s ease;
        font-size: 12px; /* Increase font size by 1px */
    }

    .project-details a:hover {
        background-color: #3498db;
    }

    .paper {
        background-color: #3498db;
    }

    .abstract {
        background-color: #2ecc71;
    }

    .project-page {
        background-color: #e74c3c;
    }

    .bibtex {
        background-color: #f39c12;
    }
</style>

<div class="container">

  <div class="project">
    <img class="project-img" src="path/to/your/image1.jpg" alt="Project 1 Image">
    <div class="project-details">
      <div class="project-title">Learning Deformable Tetrahedral Meshes for 3D Reconstruction</div>
      <div class="project-authors">Jun Gao, Wenzheng Chen, Tommy Xiang, Alec Jacobson, Morgan McGuire, Sanja Fidler</div>
      <div class="project-conference">In NeurIPS, Vancouver, 2020</div>
      <div class="project-buttons">
        <a class="paper" href="#">Paper</a>
        <a class="abstract" href="#">Abstract</a>
        <a class="project-page" href="#">Project page</a>
        <a class="bibtex" href="#">Bibtex</a>
      </div>
    </div>
  </div>

  <div class="project2">
    <img class="project-img" src="path/to/your/image2.jpg" alt="Project 2 Image">
    <div class="project-details">
      <div class="project-title">Variational Amodal Object Completion for Interactive Scene Editing</div>
      <div class="project-authors">Huan Ling, David Acuna, Karsten Kreis, Seung Kim, Sanja Fidler</div>
      <div class="project-conference">In NeurIPS, Vancouver, 2020</div>
      <div class="project-buttons">
        <a class="paper" href="#">Paper</a>
        <a class="abstract" href="#">Abstract</a>
        <a class="project-page" href="#">Project page</a>
        <a class="bibtex" href="#">Bibtex</a>
      </div>
    </div>
  </div>

  <div class="project3">
    <img class="project-img" src="path/to/your/image3.jpg" alt="Project 3 Image">
    <div class="project-details">
      <div class="project-title">Federated Simulation for Medical Imaging (nominated for Young Scientist Award)</div>
      <div class="project-authors">Daiqing Li, Amlan Kar, Nishant Ravikumar, Alejandro F Frangi, Sanja Fidler</div>
      <div class="project-conference">In MICCAI, 2020</div>
      <div class="project-buttons">
        <a class="paper" href="#">Paper</a>
        <a class="abstract" href="#">Abstract</a>
        <a class="project-page" href="#">Project page</a>
        <a class="bibtex" href="#">Bibtex</a>
      </div>
    </div>
  </div>

  <div class="project4">
    <img class="project-img" src="path/to/your/image4.jpg" alt="Project 4 Image">
    <div class="project-details">
      <div class="project-title">Lift, Splat, Shoot: Encoding Images from Arbitrary Camera Rigs by Implicitly Unprojecting to 3D</div>
      <div class="project-authors">Jonah Philion, Sanja Fidler</div>
      <div class="project-conference">In ECCV, 2020</div>
      <div class="project-buttons">
        <a class="paper" href="#">Paper</a>
        <a class="abstract" href="#">Abstract</a>
        <a class="project-page" href="#">Project page</a>
        <a class="bibtex" href="#">Bibtex</a>
      </div>
    </div>
  </div>

  <!-- Add more projects as needed -->

</div>
