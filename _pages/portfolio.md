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
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 10px;
            background-color: white;
        }

        .project-img {
            width: 60px;
            height: 60px;
            object-fit: cover;
            border-radius: 50%;
            margin-right: 10px;
        }

        .project-details {
            flex: 1;
        }

        .project-title {
            font-size: 16px;
            font-weight: bold;
            margin-bottom: 3px;
        }

        .project-authors {
            font-size: 12px;
            margin-bottom: 5px;
        }

        .project-conference {
            font-style: italic;
            font-size: 11px;
            margin-bottom: 5px;
        }

        .project-buttons {
            display: flex;
            margin-top: 5px;
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
            font-size: 11px;
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

    <div class="project">
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

    <div class="project">
        <img class="project-img" src="path/to/your/image3.jpg" alt="Project 3 Image">
        <div class="project-details">
            <div class="project-title">Federated Simulation for Medical Imaging</div>
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

    <div class="project">
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

    <div class="project">
        <img class="project-img" src="path/to/your/image5.jpg" alt="Project 5 Image">
        <div class="project-details">
            <div class="project-title">Meta-Sim2: Unsupervised Learning of Scene Structure for Synthetic Data Generation</div>
            <div class="project-authors">Jeevan Devaranjan*, Amlan Kar*, Sanja Fidler</div>
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

</body>
</html>
