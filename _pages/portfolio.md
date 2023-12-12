---
layout: archive
title: "Portfolio"
permalink: portfolio/
location: "Toronto, Canada"
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
        }

        .project {
            display: flex;
            align-items: center;
            margin-bottom: 30px;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            background-color: white;
        }

        .project-img {
            width: 80px; /* Adjust the width as needed */
            height: 80px; /* Adjust the height as needed */
            object-fit: cover;
            border-radius: 50%;
            margin-right: 20px;
        }

        .project-title {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 5px;
        }

        .project-authors {
            margin-bottom: 10px;
        }

        .project-conference {
            font-style: italic;
            margin-bottom: 10px;
        }

        .project-details {
            display: flex;
            align-items: center;
        }

        .project-details a {
            display: inline-block;
            padding: 8px 12px;
            margin-right: 10px;
            text-align: center;
            text-decoration: none;
            color: #fff;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s ease;
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
</head>
<body>

<div class="container">

    <div class="project">
        <img class="project-img" src="path/to/your/image1.jpg" alt="Project 1 Image">
        <div>
            <div class="project-title">Learning Deformable Tetrahedral Meshes for 3D Reconstruction</div>
            <div class="project-authors">Jun Gao, Wenzheng Chen, Tommy Xiang, Alec Jacobson, Morgan McGuire, Sanja Fidler</div>
            <div class="project-conference">In Neural Information Processing Systems (NeurIPS), Vancouver, Canada, 2020</div>
            <div class="project-details">
                <a class="paper" href="#">Paper</a>
                <a class="abstract" href="#">Abstract</a>
                <a class="project-page" href="#">Project page</a>
                <a class="bibtex" href="#">Bibtex</a>
            </div>
        </div>
    </div>

    <div class="project">
        <img class="project-img" src="path/to/your/image2.jpg" alt="Project 2 Image">
        <div>
            <div class="project-title">Variational Amodal Object Completion for Interactive Scene Editing</div>
            <div class="project-authors">Huan Ling, David Acuna, Karsten Kreis, Seung Kim, Sanja Fidler</div>
            <div class="project-conference">In Neural Information Processing Systems (NeurIPS), Vancouver, Canada, 2020</div>
            <div class="project-details">
                <a class="paper" href="#">Paper</a>
                <a class="abstract" href="#">Abstract</a>
                <a class="project-page" href="#">Project page</a>
                <a class="bibtex" href="#">Bibtex</a>
            </div>
        </div>
    </div>

    <!-- Add more projects as needed -->

</div>

</body>
</html>
