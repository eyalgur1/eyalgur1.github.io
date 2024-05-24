<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
            color: #fff;
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .container {
            width: 100%;
            margin: 2rem auto;
            /* max-width: 2000px; */
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
            /* max-width: 2000px; */
            flex-direction: column;
            gap: 2rem;
        }
        /* Desktop-specific layout */
        @media (min-width: 768px) {
            .sections-container {
                flex-direction: row;
                /* max-width: 1100px; */
                justify-content: space-between;
            }
        }

        .section {
            flex-basis: 48%;
            background-color: #f8f9fa;
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
        }

        .section-title-separator {
            border-top: 2px solid #ccc; /* Twice the thickness of .separator */
            margin: 1.5rem 0;
        }
        .section h2 {
            font-family: 'Roboto', sans-serif;
            color: #343a40;
            margin-bottom: 1rem;
        }
        /* Separator style */
        .separator {
            border-top: 1px solid #ccc;
            margin: 1.5rem 0;
        }
        .project {
            margin-bottom: 1.5rem;
            overflow: hidden; /* Ensure clearfix */
        }
        .project:last-child {
            margin-bottom: 0;
        }
        .project img {
            width: 170px;
            height: 170px;
            max-width: 100%; /* Ensure it scales down appropriately */
            margin-left: 1rem; /* Add margin to the left to space it from the text */
            margin-bottom: 0.5rem;
            border-radius: 10px;
            object-fit: cover;
            float: right; /* Float the image to the right */
        }
        .project-info {
            flex: 1;
        }
        .project-info h3 {
            font-family: 'Roboto', sans-serif;
            font-weight: bold;
            font-size: 24px;
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
    <div class="container">
        <div class="bio">
            <img src="path/to/yourphoto.jpg" alt="Eyal Gur">
            <p>I am a Ph.D. algorithm developer specializing in optimization problems within deep and machine learning, signal processing, data science, statistics, operations research, mathematics, and other related domains. <br> <br>My projects and ongoing endeavors, which include links to code repositories with detailed comments and PDF files, are listed below. Feel free to explore the provided links and don't hesitate to reach out to me for further information.</p>
        </div>

        <div class="sections-container">
            <div class="section">
                <h2>Publications</h2>
                <div class="projects-container">
                    <div class="project">
                        <img src="images/SNL1.jpg" alt="Sensor Network Cover Photo">
                        <div class="project-info">
                            <h3>Fast Sensor Network Localization</h3>
                            <p>A novel fast distributed and parallel method for wireless sensor network localization with data uncertainty.</p>
                            <p class="keywords"><strong>Keywords:</strong> Statistical Estimation, Distributed Parallel Computing, Optimization Algorithms</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur1/Fast_Network_Localization" target="_blank">GitHub</a>
                                <a href="pdf/FNL_paper.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="separator"></div> <!-- Add this separator -->
                    <div class="project">
                        <img src="images/SSL1.jpg" alt="Target Detection Cover Photo">
                        <div class="project-info">
                            <h3>Target Detection</h3>
                            <p>Detection of targets with a novel algorithm in an asynchronous environment using TDoA.</p>
                            <p class="keywords"><strong>Keywords:</strong> Source Localization and Detection, Fast Optimization</p>
                            <div class="links">
                                <a href="https://www.sciencedirect.com/science/article/abs/pii/S1051200423001690" target="_blank">Full Text</a>
                                <a href="https://github.com/eyalgur1/TDoA_Source_Localization" target="_blank">GitHub</a>
                                <a href="pdf/TDOA.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="separator"></div> <!-- Add this separator -->
                    <div class="project">
                        <img src="images/SSL2.jpg" alt="Synchronization and Localization Cover Photo">
                        <div class="project-info">
                            <h3>Synchronization and Localization of Targets</h3>
                            <p>Simultaneously synchronizing and locating source targets with a novel and fast algorithm.</p>
                            <p class="keywords"><strong>Keywords:</strong> Source Synchronization, Statistical Estimation, Optimization Algorithms</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur1/Asynchronous_ToA_Source_Localization" target="_blank">GitHub</a>
                                <a href="pdf/TOA.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="separator"></div> <!-- Add this separator -->
                    <div class="project">
                        <img src="images/SNL2.jpg" alt="Wireless Sensor Network Cover Photo">
                        <div class="project-info">
                            <h3>Wireless Sensor Network Localization</h3>
                            <p>Fully distributed to fully centralized novel algorithms for locating complex sensor networks.</p>
                            <p class="keywords"><strong>Keywords:</strong> Distributed Optimization, Parallel Computing, Network Simulations</p>
                            <div class="links">
                                <a href="https://ieeexplore.ieee.org/abstract/document/9226609" target="_blank">Full Text</a>
                                <a href="https://github.com/eyalgur1/Sensor_Network_Localization" target="_blank">GitHub</a>
                                <a href="pdf/WSNL.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="separator"></div> <!-- Add this separator -->
                    <div class="project">
                        <img src="images/ID.jpg" alt="Image Deblurring Cover Photo">
                        <div class="project-info">
                            <h3>Image Deblurring</h3>
                            <p>Reconstructing a blurred image with a new algorithm with regularization.</p>
                            <p class="keywords"><strong>Keywords:</strong> Image Processing, Elastic Net, Image Reconstruction</p>
                            <div class="links">
                                <a href="https://link.springer.com/article/10.1007/s10957-023-02310-4" target="_blank">Full Text</a>
                                <a href="https://github.com/eyalgur1/Image_Deblurring/tree/main/non_smooth" target="_blank">GitHub</a>
                                <a href="pdf/NAM2.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="separator"></div> <!-- Add this separator -->
                    <div class="project">
                        <img src="images/NAM.jpg" alt="Neted Alternating Minimization Cover Photo">
                        <div class="project-info">
                            <h3>Nested Algorithm for Complex Optimization Problems</h3>
                            <p>A novel and practical algorithmic framework that solves non-convex optimization problems by nesting algorithms.</p>
                            <p class="keywords"><strong>Keywords:</strong> Optimization, Fast Algorithms, Analysis</p>
                            <div class="links">
                                <a href="https://pubsonline.informs.org/doi/abs/10.1287/moor.2022.1256" target="_blank">Full Text</a>
                                <a href="https://github.com/eyalgur1/Image_Deblurring/tree/main/smooth" target="_blank">GitHub</a>
                                <a href="pdf/NAM1.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="separator"></div> <!-- Add this separator -->
                    <div class="project">
                        <img src="images/MDS.jpg" alt="Optimality in Networks Cover Photo">
                        <div class="project-info">
                            <h3>Optimality in Multi-Dimensional Scaling and Networks</h3>
                            <p>Optimality of solutions in the sensor networks and dimensionality reduction in unsupervised learning.</p>
                            <p class="keywords"><strong>Keywords:</strong> Heuristics for Optimality, Unsupervised Learning, Sensor Networks, Algorithm Analysis</p>
                            <div class="links">
                                <a href="pdf/SNL.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="section">
                <h2>Exploratory Projects</h2>
                <div class="projects-container">
                    <div class="project">
                        <img src="images/AE.jpg" alt="Auto-EncoderOptimizer Cover Photo">
                        <div class="project-info">
                            <h3>Auto-Encoder Neural Network Optimizer</h3>
                            <p>An auto-encoder neural network with a custom optimizer developed to tackle a toy image encoding and decoding task for computer vision, compared to ADAM.</p>
                            <p class="keywords"><strong>Keywords:</strong> Deep Learning, Optimizers, Image Processing, Computer Vision, Python</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur1/AutoEncoders" target="_blank">GitHub</a>
                                <a href="pdf/AE.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="separator"></div> <!-- Add this separator -->
                    <div class="project">
                        <img src="images/CV.jpg" alt="Computer Vision Cover Photo">
                        <div class="project-info">
                            <h3>Computer Vision</h3>
                            <p>Algorithms and deep learning techniques for computer vision tasks with explanations and code, following the Hugging Face CV Course.</p>
                            <p class="keywords"><strong>Keywords:</strong> Deep Learning, Feature Matching, Convolution Neural Networks, Transformers</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur1/Computer_Vision__Huggning_Face_Community_CV_Course" target="_blank">GitHub</a>
                                <a href="pdf/CV.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="separator"></div> <!-- Add this separator -->
                    <div class="project">
                        <img src="images/NLP.jpg" alt="Natural Language Processing Cover Photo">
                        <div class="project-info">
                            <h3>Large Language Model for NLP</h3>
                            <p>The transformer architecture of large language models for Natural Languge Processing explained from a mathematical perspective.</p>
                            <p class="keywords"><strong>Keywords:</strong> NLP, LLM, PyTorch, Transformers</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur1/Large_Language_Models_Explained" target="_blank">GitHub</a>
                                <a href="pdf/LLM.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="separator"></div> <!-- Add this separator -->
                    <div class="project">
                        <img src="images/ML.jpg" alt="Machine Learning Techniques Cover Photo">
                        <div class="project-info">
                            <h3>Machine Learning Techniques</h3>
                            <p>Foundational techniques in machine learning for data science with explanations and python code.</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur1/Machine_Learning_Techniques" target="_blank">GitHub</a>
                            </div>
                        </div>
                    </div>
                    <div class="separator"></div> <!-- Add this separator -->
                    <div class="project">
                        <img src="images/RSP.jpg" alt="Radar Signal Processing Cover Photo">
                        <div class="project-info">
                            <h3>Radar Signal Processing</h3>
                            <p>Detecting a moving target using Doppler maps with python code and explanations.</p>
                            <p class="keywords"><strong>Keywords:</strong> Radar, Detection, Doppler Map, Python</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur1/Radar_Signal_Processing" target="_blank">GitHub</a>
                                <a href="pdf/Radar_Signal_Processing.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                    <div class="separator"></div> <!-- Add this separator -->
                    <div class="project">
                        <img src="images/PL.jpg" alt="Motion Planning Cover Photo">
                        <div class="project-info">
                            <h3>Motion Planning</h3>
                            <p>Motion and path planning of a robot that maps corners in constant speed, with explanations.</p>
                            <p class="keywords"><strong>Keywords:</strong> Motion Planning, Path Planning, Non-Smooth</p>
                            <div class="links">
                                <a href="https://github.com/eyalgur1/Path_Planning_for_Corner" target="_blank">GitHub</a>
                                <a href="pdf/PL.pdf" target="_blank">PDF</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
