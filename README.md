<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eyal Gur - Projects</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 2rem;
            background: #fff;
            margin-top: 2rem;
        }
        .bio {
            text-align: center;
            margin-bottom: 2rem;
        }
        .bio img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }
        .sections-container {
            display: flex;
            justify-content: space-between;
        }
        .section {
            flex-basis: 48%;
        }
        .project {
            border-bottom: 1px solid #ccc;
            padding-bottom: 1rem;
            margin-bottom: 1rem;
            display: flex;
        }
        .project:last-child {
            border-bottom: none;
        }
        .project img {
            width: 150px;
            height: 150px;
            margin-right: 1rem;
            border-radius: 5px;
        }
        h2, h3 {
            color: #333;
        }
        p {
            color: #555;
        }
        a {
            color: #007bff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .links a {
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Eyal Gur - Projects</h1>
    </header>
    <div class="container">
        <div class="bio">
            <img src="path/to/yourphoto.jpg" alt="Eyal Gur">
            <p>Short biographic description. Eyal Gur is a researcher in the field of computer science with a focus on machine learning and data analysis...</p>
        </div>

        <div class="sections-container">
            <div class="section">
                <h2>Publications</h2>
                <div class="projects-container">
                    <div class="project">
                        <img src="path/to/publication1_cover.jpg" alt="Publication 1 Cover Photo">
                        <div class="project-info">
                            <h3>Publication Title 1</h3>
                            <p>Short description of the publication. This paper discusses...</p>
                            <div class="links">
                                <a href="https://link-to-publication.com" target="_blank">Full Text</a>
                                <a href="https://github.com/yourusername/publication1" target="_blank">GitHub</a>
                                <a href="path/to/publication1.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <!-- Add more publication projects as needed -->
                </div>
            </div>

            <div class="section">
                <h2>Exploratory Projects</h2>
                <div class="projects-container">
                    <div class="project">
                        <img src="path/to/exploration1_cover.jpg" alt="Exploration 1 Cover Photo">
                        <div class="project-info">
                            <h3>Exploration Title 1</h3>
                            <p>Short description of the exploration project. This project explores...</p>
                            <div class="links">
                                <a href="https://github.com/yourusername/exploration1" target="_blank">GitHub</a>
                                <!-- You can add more links or information as needed -->
                            </div>
                        </div>
                    </div>
                    <!-- Add more exploratory projects as needed -->
                </div>
            </div>
        </div>
    </div>
</body>
</html>
