<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salvatore Lizio - Finance Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        
        header {
            background: #0077b6;
            color: #fff;
            padding: 30px 0;
            text-align: center;
        }
        
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        
        header p {
            margin: 10px 0 0;
            font-size: 1.2rem;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 30px auto;
        }
        
        section {
            margin-bottom: 40px;
        }
        
        h2 {
            color: #0077b6;
            border-bottom: 2px solid #0077b6;
            padding-bottom: 10px;
        }
        
        .project, .skill {
            background: #fff;
            padding: 20px;
            margin-bottom: 15px;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        
        .project:hover, .skill:hover {
            transform: translateY(-5px);
        }
        
        .project h3, .skill h3 {
            margin-top: 0;
            color: #0077b6;
        }
        
        a {
            color: #0077b6;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        
        a:hover {
            color: #005a8d;
        }
        
        .btn {
            display: inline-block;
            background: #0077b6;
            color: white;
            padding: 10px 15px;
            border-radius: 5px;
            margin-top: 10px;
        }
        
        .btn:hover {
            background: #005a8d;
            color: white;
            text-decoration: none;
        }
        
        footer {
            background: #0077b6;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }
        
        @media (max-width: 768px) {
            .container {
                width: 95%;
            }
            
            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Salvatore Lizio</h1>
        <p>Risk Analyst @Morgan Stanley & CFA Level 2 Candidate</p>
    </header>

    <div class="container">
        <!-- About Me Section -->
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I'm a finance professional with an insatiable passion for Markets. I am currently working in Morgan Stanley as a Risk Analyst, where I enjoy solving complex financial problems and building tools to streamline processes. I am a firm believer of the short-term inefficiency of the Stock market, and I like to do my research and exploit opportunities.</p>
        </section>

        <!-- Resume/CV Section -->
        <section id="resume">
            <h2>Resume/CV</h2>
            <p>Download my resume: <a href="CV_Salvatore Lizio_def.pdf" download class="btn">Download PDF</a></p>
        </section>

        <!-- Projects Section -->
        
        <section id="projects">


        https://beneish-m-score.streamlit.app/
        
            <h2>Projects</h2>
            
            <div class="project">
                <h3>Beneish M-Score</h3>
                <p>Built an app to calculate the Beneish M-Score using Python and Streamlit.</p>
                <a href="https://beneish-m-score.streamlit.app/" target="_blank" class="btn">View Code</a>
            </div>
            
            
            <div class="project">
                <h3>Black-Scholes-Merton Model for Option Pricing</h3>
                <p>Built an Option Pricing model using the BSM (Black-Scholes-Merton) model with Python.</p>
                <a href="https://github.com/lizio27/portfolio/blob/262675d7c32a39cdab2a6d08a3c808f28e2b43a4/BSM%20model%20for%20Option%20Valuation.ipynb" target="_blank" class="btn">View Code</a>
            </div>
            
            <div class="project">
            
                <h3>Efficient Frontier Portfolio</h3>
                <p>Developed a tool to optimize investment portfolios using Modern Portfolio Theory and Python.</p>
                <a href="https://github.com/lizio27/portfolio/blob/a3f1abbc5b3a9b33dd36dffe9d2538d17fa5d9e5/Efficient%20Frontier.ipynb" target="_blank" class="btn">View Code</a>
            </div>
            
        </section>
    

        <!-- Skills Section -->
        <section id="skills">
            <h2>Skills</h2>
            <div class="skill">
                <h3>Technical Skills</h3>
                <p>Python, R, SQL, Excel, Tableau, Power BI, Financial Modeling</p>
            </div>
            <div class="skill">
                <h3>Finance Skills</h3>
                <p>Valuation, Risk Analysis, Portfolio Management, Financial Reporting</p>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:liziobusiness@outlook.com">liziobusiness@outlook.com</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/salvatore-lizio/" target="_blank">Salvatore Lizio</a></p>
            <p>GitHub: <a href="https://github.com/lizio27" target="_blank">github.com/lizio27</a></p>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Salvatore Lizio. All rights reserved.</p>
    </footer>
</body>
</html>
