<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eyal Gur - Projects</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
        header {
            background-color: #343a40;
            color: #fff;
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .container {
            width: 85%;
            margin: 2rem auto;
            padding: 2rem;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .bio {
            text-align: center;
            margin-bottom: 2rem;
        }
        .bio img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 1rem;
        }
        .bio p {
            font-size: 1.1rem;
            color: #555;
        }
        .sections-container {
            display: flex;
            justify-content: space-between;
            gap: 2rem;
        }
        .section {
            flex: 1;
            background-color: #f8f9fa;
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
        }
        .section h2 {
            color: #343a40;
            margin-bottom: 1rem;
        }
        .project {
            display: flex;
            align-items: flex-start;
            margin-bottom: 1.5rem;
        }
        .project:last-child {
            margin-bottom: 0;
        }
        .project img {
            width: 120px;
            height: 120px;
            margin-right: 1rem;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .project-info {
            flex: 1;
        }
        .project-info h3 {
            margin: 0 0 0.5rem;
            color: #343a40;
        }
        .project-info p {
            margin: 0 0 0.5rem;
            color: #555;
        }
        .links a {
            display: inline-block;
            margin-right: 10px;
            color: #007bff;
            text-decoration: none;
            transition: color 0.3s;
        }
        .links a:hover {
            color: #0056b3;
            text-decoration: underline;
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
            <p>I am currently pursuing a PhD in Data Science and Optimization, focusing on developing innovative solutions in machine learning, statistical estimation, and optimization algorithms.</p>
        </div>

        <div class="sections-container">
            <div class="section">
                <h2>Publications</h2>
                <div class="projects-container">
                    <div class="project">
                        <img src="path/to/sensor_network_cover.jpg" alt="Sensor Network Cover Photo">
                        <div class="project-info">
                            <h3>Sensor Network Localization</h3>
                            <p>A novel fast distributed and parallel method for wireless sensor network localization with data uncertainty.</p>
                            <p><strong>Keywords:</strong> Statistical Estimation, Distributed Parallel Computing, Optimization Algorithms</p>
                            <div class="links">
                                <a href="https://link-to-publication.com" target="_blank">Full Text</a>
                                <a href="https://github.com/eyalgur/sensor-network-localization" target="_blank">GitHub</a>
                                <a href="path/to/sensor_network_publication.pdf" target="_blank">PDF</a>
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
                        <img src="path/to/autoencoder_optimizer_cover.jpg" alt="AutoEncoder Optimizer Cover Photo">
                        <div class="project-info">
                            <h3>AutoEncoder Optimizer</h3>
                            <p>An auto-encoder neural network with a custom optimizer developed to tackle a toy image encoding and decoding task for computer vision, compared to ADAM.</p>
                            <p><strong>Keywords:</strong> Deep Learning, Optimizers, Image Processing, Computer Vision, Python</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur/autoencoder-optimizer" target="_blank">GitHub</a>
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
