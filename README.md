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
            width: 100%;
            max-width: 2000px;
            color: #fff;
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .container {
            width: 100%;
            margin: 2rem auto;
            max-width: 2000px;
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
            max-width: 1800px;
            justify-content: space-between;
            gap: 2rem;
        }
        .section {
            flex-basis: 48%;
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
            width: 170px;
            height: 170px;
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
        .project-info .keywords {
            font-size: 0.9rem;
            color: #777;
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
                        <img src="images/SNL1.jpg" alt="Sensor Network Cover Photo">
                        <div class="project-info">
                            <h3>Sensor Network Localization</h3>
                            <p>A novel fast distributed and parallel method for wireless sensor network localization with data uncertainty.</p>
                            <p class="keywords"><strong>Keywords:</strong> Statistical Estimation, Distributed Parallel Computing, Optimization Algorithms</p>
                            <div class="links">
                                <a href="https://link-to-publication.com" target="_blank">Full Text</a>
                                <a href="https://github.com/eyalgur/sensor-network-localization" target="_blank">GitHub</a>
                                <a href="path/to/sensor_network_publication.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="project">
                        <img src="images/SSL1.jpg" alt="Target Detection Cover Photo">
                        <div class="project-info">
                            <h3>Target Detection</h3>
                            <p>Detection of targets with a novel algorithm in an asynchronous environment using TDoA.</p>
                            <p class="keywords"><strong>Keywords:</strong> Source Localization and Detection, Fast Optimization</p>
                            <div class="links">
                                <a href="https://link-to-publication.com" target="_blank">Full Text</a>
                                <a href="https://github.com/eyalgur/target-detection" target="_blank">GitHub</a>
                                <a href="path/to/target_detection_publication.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="project">
                        <img src="images/SSL2.jpg" alt="Synchronization and Localization Cover Photo">
                        <div class="project-info">
                            <h3>Synchronization and Localization of Targets</h3>
                            <p>Simultaneously synchronizing and locating source targets with a novel and fast algorithm.</p>
                            <p class="keywords"><strong>Keywords:</strong> Source Synchronization, Statistical Estimation, Optimization Algorithms</p>
                            <div class="links">
                                <a href="https://link-to-publication.com" target="_blank">Full Text</a>
                                <a href="https://github.com/eyalgur/synchronization-localization" target="_blank">GitHub</a>
                                <a href="path/to/synchronization_localization_publication.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="project">
                        <img src="images/SNL2.jpg" alt="Wireless Sensor Network Cover Photo">
                        <div class="project-info">
                            <h3>Wireless Sensor Network Localization</h3>
                            <p>Fully distributed to fully centralized novel algorithms for locating complex sensor networks.</p>
                            <p class="keywords"><strong>Keywords:</strong> Distributed Optimization, Parallel Computing, Network Simulations</p>
                            <div class="links">
                                <a href="https://link-to-publication.com" target="_blank">Full Text</a>
                                <a href="https://github.com/eyalgur/wireless-sensor-network-localization" target="_blank">GitHub</a>
                                <a href="path/to/wireless_sensor_network_publication.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="project">
                        <img src="images/ID.jpg" alt="Image Deblurring Cover Photo">
                        <div class="project-info">
                            <h3>Image Deblurring</h3>
                            <p>Reconstructing a blurred image with a new algorithm with regularization.</p>
                            <p class="keywords"><strong>Keywords:</strong> Image Processing, Elastic Net, Image Reconstruction</p>
                            <div class="links">
                                <a href="https://link-to-publication.com" target="_blank">Full Text</a>
                                <a href="https://github.com/eyalgur/image-deblurring" target="_blank">GitHub</a>
                                <a href="path/to/image_deblurring_publication.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="project">
                        <img src="images/NAM.jpg" alt="Neted Alternating Minimization Cover Photo">
                        <div class="project-info">
                            <h3>Neted Alternating Minimization</h3>
                            <p>A novel and practical algorithmic framework that solves complex optimization problems.</p>
                            <p class="keywords"><strong>Keywords:</strong> Optimization, Fast Algorithms, Analysis</p>
                            <div class="links">
                                <a href="https://link-to-publication.com" target="_blank">Full Text</a>
                                <a href="https://github.com/eyalgur/neted-alternating-minimization" target="_blank">GitHub</a>
                                <a href="path/to/neted_alternating_minimization_publication.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="project">
                        <img src="images/MDS.jpg" alt="Optimality in Networks Cover Photo">
                        <div class="project-info">
                            <h3>Optimality in Networks and Multi-Dimensional Scaling</h3>
                            <p>Optimality of solutions in the sensor networks and dimensionality reduction in unsupervised learning.</p>
                            <p class="keywords"><strong>Keywords:</strong> Heuristics for Optimality, Unsupervised Learning, Sensor Networks, Algorithm Analysis</p>
                            <div class="links">
                                <a href="https://link-to-publication.com" target="_blank">Full Text</a>
                                <a href="https://github.com/eyalgur/optimality-networks-scaling" target="_blank">GitHub</a>
                                <a href="path/to/optimality_networks_scaling_publication.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2>Exploratory Projects</h2>
                <div class="projects-container">
                    <div class="project">
                        <img src="images/AE.jpg" alt="AutoEncoder Optimizer Cover Photo">
                        <div class="project-info">
                            <h3>AutoEncoder Optimizer</h3>
                            <p>An auto-encoder neural network with a custom optimizer developed to tackle a toy image encoding and decoding task for computer vision, compared to ADAM.</p>
                            <p class="keywords"><strong>Keywords:</strong> Deep Learning, Optimizers, Image Processing, Computer Vision, Python</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur/autoencoder-optimizer" target="_blank">GitHub</a>
                            </div>
                        </div>
                    </div>
                    <div class="project">
                        <img src="images/CV.jpg" alt="Computer Vision Cover Photo">
                        <div class="project-info">
                            <h3>Computer Vision</h3>
                            <p>Algorithms and deep learning techniques for computer vision tasks with explanations and code, following the Hugging Face CV Course.</p>
                            <p class="keywords"><strong>Keywords:</strong> Deep Learning, Feature Matching, Convolution Neural Networks, Transformers</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur/computer-vision" target="_blank">GitHub</a>
                                <a href="path/to/computer_vision.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="project">
                        <img src="images/NLP.jpg" alt="Natural Language Processing Cover Photo">
                        <div class="project-info">
                            <h3>Natural Language Processing</h3>
                            <p>The transformer architecture for large language models explained from a mathematical perspective.</p>
                            <p class="keywords"><strong>Keywords:</strong> NLP, LLM, PyTorch, Transformers</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur/natural-language-processing" target="_blank">GitHub</a>
                                <a href="path/to/natural_language_processing.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="project">
                        <img src="images/ML.jpg" alt="Machine Learning Techniques Cover Photo">
                        <div class="project-info">
                            <h3>Machine Learning Techniques</h3>
                            <p>Foundational techniques in machine learning for data science with explanations and python code.</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur/machine-learning-techniques" target="_blank">GitHub</a>
                            </div>
                        </div>
                    </div>
                    <div class="project">
                        <img src="images/RSP.jpg" alt="Radar Signal Processing Cover Photo">
                        <div class="project-info">
                            <h3>Radar Signal Processing</h3>
                            <p>Detecting a moving target using Doppler maps with python code and explanations.</p>
                            <p class="keywords"><strong>Keywords:</strong> Radar, Detection, Doppler Map, Python</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur/radar-signal-processing" target="_blank">GitHub</a>
                                <a href="path/to/radar_signal_processing.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="project">
                        <img src="images/PL.jpg" alt="Motion Planning Cover Photo">
                        <div class="project-info">
                            <h3>Motion Planning</h3>
                            <p>Motion planning of a robot that maps corners in constant speed, with explanations.</p>
                            <p class="keywords"><strong>Keywords:</strong> Motion Planning, Path Planning, Non-Smooth</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur/motion-planning" target="_blank">GitHub</a>
                                <a href="path/to/motion_planning.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
