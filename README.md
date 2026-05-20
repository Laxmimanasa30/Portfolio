<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laxmi Manasa Tumuluri | Portfolio</title>
    <style>
        :root {
            --primary: #2c5282;
            --secondary: #3182ce;
            --bg-light: #f7fafc;
            --text-dark: #2d3748;
            --text-light: #718096;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--bg-light);
            color: var(--text-dark);
            line-height: 1.6;
        }
        header {
            background-color: var(--primary);
            color: white;
            padding: 4rem 2rem;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
            letter-spacing: 1px;
        }
        header p {
            font-size: 1.2rem;
            color: #e2e8f0;
            margin-top: 0.5rem;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 2rem;
        }
        section {
            margin-bottom: 3rem;
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }
        h2 {
            color: var(--primary);
            border-bottom: 2px solid #edf2f7;
            padding-bottom: 0.5rem;
            margin-top: 0;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
        }
        .card {
            border: 1px solid #e2e8f0;
            padding: 1.5rem;
            border-radius: 6px;
            transition: transform 0.2s;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px rgba(0,0,0,0.1);
        }
        .card h3 {
            margin-top: 0;
            color: var(--secondary);
        }
        .tags {
            margin-top: 1rem;
        }
        .tag {
            display: inline-block;
            background: #edf2f7;
            color: var(--primary);
            padding: 0.2rem 0.6rem;
            border-radius: 999px;
            font-size: 0.8rem;
            margin-right: 0.5rem;
            margin-bottom: 0.5rem;
        }
        .contact-links a {
            color: var(--secondary);
            text-decoration: none;
            margin-right: 1rem;
            font-weight: bold;
        }
        .contact-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <h1>Laxmi Manasa Tumuluri</h1>
        <p>Information Technology Student | AI Generalist & Data Scientist</p>
    </header>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>I am a highly motivated Information Technology student with a strong foundation in Python, Java, AI/ML, and web development. Passionate about solving real-world problems using Data Structures, Machine Learning, Deep Learning, and Agent Training. I am currently honing my skills in AI reasoning and model evaluation to contribute to innovative AI-driven solutions.</p>
        </section>

        <section id="experience">
            <h2>Experience</h2>
            <div class="card">
                <h3>Deccan AI | Operations Associate & AI Generalist</h3>
                <p><em>October 2025 - Present | Hyderabad, India</em></p>
                <ul>
                    <li>Manage and coordinate team operations within a dynamic production environment.</li>
                    <li>Serve as an AI Research Contributor focusing on AI reasoning, prompt engineering, and rigorous AI model evaluation.</li>
                    <li>Train and evaluate intelligent agents within RL Gym environments.</li>
                </ul>
            </div>
        </section>

        <section id="projects">
            <h2>Featured Projects</h2>
            <div class="grid">
                <div class="card">
                    <h3>Vintage Flavours</h3>
                    <p>Designed and developed an AI-driven recipe recommendation platform focused specifically on vegetarian cuisine. Engineered filtering and matching algorithms to provide highly personalized meal suggestions.</p>
                    <div class="tags">
                        <span class="tag">Recommendation System</span>
                        <span class="tag">AI</span>
                        <span class="tag">Algorithms</span>
                    </div>
                </div>

                <div class="card">
                    <h3>Sentiment Analysis using CNN</h3>
                    <p>Designed and implemented a Convolutional Neural Network (CNN) model to classify text reviews into positive or negative sentiments with 91% accuracy.</p>
                    <div class="tags">
                        <span class="tag">Python</span>
                        <span class="tag">TensorFlow</span>
                        <span class="tag">NLP</span>
                    </div>
                </div>

                <div class="card">
                    <h3>YOLO-Based Object Detection</h3>
                    <p>Developed an object detection system using the YOLO algorithm to identify and classify objects in images and real-time video streams for traffic rule violation detection.</p>
                    <div class="tags">
                        <span class="tag">OpenCV</span>
                        <span class="tag">Python</span>
                        <span class="tag">YOLO</span>
                    </div>
                </div>

                <div class="card">
                    <h3>Smart Customer Churn Prediction</h3>
                    <p>Built an AI-driven churn prediction pipeline using synthetic e-commerce customer data to identify potential churners and improve retention strategies, improving accuracy by 15%.</p>
                    <div class="tags">
                        <span class="tag">XGBoost</span>
                        <span class="tag">SHAP</span>
                        <span class="tag">LIME</span>
                    </div>
                </div>
            </div>
        </section>

        <section id="skills">
            <h2>Technical Skills</h2>
            <div class="tags">
                <span class="tag">Python</span>
                <span class="tag">Java</span>
                <span class="tag">SQL</span>
                <span class="tag">TensorFlow</span>
                <span class="tag">Keras</span>
                <span class="tag">Scikit-learn</span>
                <span class="tag">OpenCV</span>
                <span class="tag">Deep Learning</span>
                <span class="tag">NLP</span>
                <span class="tag">Prompt Engineering</span>
                <span class="tag">RL Gym</span>
                <span class="tag">AWS</span>
                <span class="tag">Google Big Query</span>
                <span class="tag">Power BI</span>
            </div>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p class="contact-links">
                <a href="mailto:laxmimanasatumuluri@gmail.com">laxmimanasatumuluri@gmail.com</a>
                <a href="tel:7396594372">7396594372</a>
                <a href="#">LinkedIn</a>
            </p>
        </section>
    </div>

</body>
</html>
