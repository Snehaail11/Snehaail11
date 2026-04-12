<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sneha Ail · AI & Data Science</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      background: #0A0A0A;
      font-family: 'Inter', sans-serif;
      color: #E5E5E5;
      padding: 2rem 1.5rem;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      background: #111111;
      border-radius: 1.5rem;
      padding: 2rem;
      border: 1px solid #2A2A2A;
      position: relative;
    }
    .animation-top-right {
      position: absolute;
      top: 1rem;
      right: 1rem;
    }
    lottie-player { width: 80px; height: 80px; }
    .name-section { text-align: center; margin-bottom: 2rem; }
    h1 {
      font-size: 3.5rem;
      font-weight: 800;
      background: linear-gradient(135deg, #FF4444 0%, #FF6B6B 40%, #E50914 100%);
      background-clip: text;
      -webkit-background-clip: text;
      color: transparent;
      margin-bottom: 0.5rem;
    }
    .role-text { font-size: 1.1rem; font-weight: 500; color: #CECECE; }
    .role-text i { color: #E50914; margin-right: 6px; }
    h2 {
      font-size: 1.6rem;
      margin: 2rem 0 1rem;
      border-left: 3px solid #E50914;
      padding-left: 1rem;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .about-panel {
      background: #0C0C0C;
      border-radius: 1rem;
      padding: 1.2rem;
      margin-bottom: 1rem;
      border-left: 3px solid #E50914;
    }
    .tech-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 0.8rem;
      margin: 1rem 0;
    }
    .tech-item {
      background: #1A1A1A;
      padding: 0.5rem 1.2rem;
      border-radius: 2rem;
      font-size: 0.85rem;
      border: 1px solid #2C2C2C;
      transition: 0.2s;
    }
    .tech-item i { margin-right: 6px; color: #E50914; }
    .tech-item:hover { transform: translateY(-2px); border-color: #E50914; }
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(340px, 1fr));
      gap: 1.5rem;
      margin: 1.5rem 0;
    }
    .project-card {
      background: #131313;
      border-radius: 1rem;
      padding: 1.3rem;
      border: 1px solid #262626;
      transition: 0.2s;
    }
    .project-card:hover { transform: translateY(-4px); border-color: #E50914; }
    .project-title {
      font-size: 1.2rem;
      font-weight: 700;
      margin-bottom: 0.5rem;
      display: flex;
      align-items: center;
      gap: 8px;
    }
    .project-title i { color: #E50914; }
    .project-desc { color: #B0B0B0; font-size: 0.85rem; margin: 0.5rem 0; line-height: 1.5; }
    .project-tech { display: flex; flex-wrap: wrap; gap: 8px; margin: 10px 0; }
    .project-tech span {
      background: #0A0A0A;
      padding: 0.2rem 0.7rem;
      border-radius: 20px;
      font-size: 0.7rem;
      border: 1px solid #2F2F2F;
      color: #E50914;
    }
    .project-media {
      margin: 1rem 0;
      border-radius: 0.5rem;
      overflow: hidden;
      text-align: center;
    }
    .project-media img {
      width: 100%;
      border-radius: 0.5rem;
      object-fit: cover;
    }
    .project-media iframe {
      width: 100%;
      aspect-ratio: 16/9;
      border: none;
      border-radius: 0.5rem;
    }
    .emoji-media {
      font-size: 4rem;
      padding: 1.5rem;
      background: #0A0A0A;
      border-radius: 0.5rem;
      text-align: center;
    }
    .project-link {
      display: inline-block;
      margin-top: 0.5rem;
      color: #E50914;
      text-decoration: none;
      font-weight: 600;
      font-size: 0.85rem;
    }
    .project-link:hover { text-decoration: underline; }
    .freelance-section {
      margin-top: 2rem;
      background: #0E0E0E;
      border-radius: 1rem;
      padding: 1.5rem;
      text-align: center;
      border: 1px solid #2A2A2A;
    }
    .contact-icons {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      margin-top: 1rem;
      flex-wrap: wrap;
    }
    .contact-icon {
      background: #1A1A1A;
      padding: 0.8rem 1.5rem;
      border-radius: 3rem;
      text-decoration: none;
      color: #E5E5E5;
      display: inline-flex;
      align-items: center;
      gap: 10px;
      transition: 0.2s;
      border: 1px solid #2F2F2F;
    }
    .contact-icon i { color: #E50914; }
    .contact-icon:hover { background: #E50914; color: white; }
    .contact-icon:hover i { color: white; }
    hr { border-color: #2A2A2A; margin: 1rem 0; }
    @media (max-width: 640px) {
      h1 { font-size: 2.5rem; }
      .role-text { font-size: 0.9rem; }
      lottie-player { width: 60px; height: 60px; }
      .emoji-media { font-size: 2.5rem; padding: 1rem; }
    }
  </style>
</head>
<body>

<div class="container">
  
  <!-- LOTTIE ANIMATION -->
  <div class="animation-top-right">
    <lottie-player 
      src="https://github.com/user-attachments/files/26655352/website.design.json" 
      background="transparent" 
      speed="1" 
      loop 
      autoplay>
    </lottie-player>
  </div>

  <!-- NAME SECTION -->
  <div class="name-section">
    <h1>Sneha Ail</h1>
    <div class="role-text">
      <i class="fas fa-microchip"></i> AI · Data Science · Product Strategy
    </div>
  </div>

  <!-- ABOUT ME -->
  <h2><i class="fas fa-user-astronaut"></i> About Me</h2>
  <div class="about-panel">
    <p>I'm interested in understanding how people think and make decisions, and using that to build better, more practical products. With a background in data science, I enjoy working at the intersection of data, AI, and product — turning ideas into tools that people can actually use. I've worked on building an internal data platform during my internship, exploring both technical implementation and product-side decision making. Currently, I'm focused on projects that combine simple AI concepts with real-world usability.</p>
  </div>

  <!-- TECH STACK -->
  <h2><i class="fas fa-microchip"></i> Tech Stack</h2>
  <div class="tech-grid">
    <span class="tech-item"><i class="fab fa-python"></i> Python</span>
    <span class="tech-item"><i class="fas fa-database"></i> Pandas</span>
    <span class="tech-item"><i class="fas fa-database"></i> PostgreSQL</span>
    <span class="tech-item"><i class="fas fa-database"></i> MySQL</span>
    <span class="tech-item"><i class="fab fa-aws"></i> AWS</span>
    <span class="tech-item"><i class="fab fa-react"></i> React</span>
    <span class="tech-item"><i class="fab fa-git-alt"></i> Git</span>
    <span class="tech-item"><i class="fab fa-docker"></i> Docker</span>
    <span class="tech-item"><i class="fas fa-chart-line"></i> Power BI</span>
    <span class="tech-item"><i class="fas fa-chart-bar"></i> Tableau</span>
    <span class="tech-item"><i class="fas fa-vial"></i> Postman</span>
    <span class="tech-item"><i class="fas fa-code"></i> VS Code</span>
    <span class="tech-item"><i class="fas fa-chart-bar"></i> NumPy</span>
    <span class="tech-item"><i class="fas fa-chart-pie"></i> Matplotlib</span>
    <span class="tech-item"><i class="fas fa-chart-line"></i> Scikit-learn</span>
    <span class="tech-item"><i class="fas fa-brain"></i> NLTK</span>
  </div>

  <!-- PROJECTS -->
  <h2><i class="fas fa-cube"></i> Featured Projects</h2>
  <div class="projects-grid">

    <!-- Data Cleaning in SQL -->
    <div class="project-card">
      <div class="project-title"><i class="fas fa-database"></i> Data Cleaning in SQL</div>
      <div class="project-desc">Cleaned and transformed a raw layoff dataset using SQL techniques: removing duplicates, standardizing values, handling nulls.</div>
      <div class="project-tech"><span>SQL</span><span>MySQL</span></div>
      <div class="project-media">
        <iframe src="https://www.youtube.com/embed/sM5-l_BXFIY" frameborder="0" allowfullscreen></iframe>
      </div>
      <a href="https://github.com/Snehaail11/mysqldataclean" class="project-link" target="_blank">View Project →</a>
    </div>

    <!-- Credit Score Prediction -->
    <div class="project-card">
      <div class="project-title"><i class="fas fa-credit-card"></i> Credit Score Prediction</div>
      <div class="project-desc">Predicts credit score based on financial data using machine learning models.</div>
      <div class="project-tech"><span>Python</span><span>Scikit-learn</span><span>Pandas</span></div>
      <div class="project-media">
        <iframe src="https://www.youtube.com/embed/5C3YaPFAAN8" frameborder="0" allowfullscreen></iframe>
      </div>
      <a href="https://github.com/Snehaail11/creditscore" class="project-link" target="_blank">View Project →</a>
    </div>

    <!-- EDA in SQL -->
    <div class="project-card">
      <div class="project-title"><i class="fas fa-chart-line"></i> EDA in SQL</div>
      <div class="project-desc">Comprehensive SQL-based EDA on tech layoffs using CTEs and window functions.</div>
      <div class="project-tech"><span>SQL</span><span>MySQL</span></div>
      <div class="project-media">
        <iframe src="https://www.youtube.com/embed/EVmwGkism0A" frameborder="0" allowfullscreen></iframe>
      </div>
      <a href="https://github.com/Snehaail11/eda" class="project-link" target="_blank">View Project →</a>
    </div>

    <!-- Supply Chain Forecasting (IMAGE) -->
    <div class="project-card">
      <div class="project-title"><i class="fas fa-boxes"></i> Supply Chain Forecasting</div>
      <div class="project-desc">Forecasts retail product demand using ML and visualizes results in Power BI.</div>
      <div class="project-tech"><span>Python</span><span>Power BI</span><span>Statsmodels</span></div>
      <div class="project-media">
        <img src="https://github.com/user-attachments/assets/76d5ce49-6ac9-4469-a1dd-de4ec860f094" alt="Supply Chain Dashboard">
      </div>
      <a href="https://github.com/Snehaail11/supplychain" class="project-link" target="_blank">View Project →</a>
    </div>

    <!-- Fraud Detection (IMAGE) -->
    <div class="project-card">
      <div class="project-title"><i class="fas fa-shield-alt"></i> Fraud Detection</div>
      <div class="project-desc">ML system identifying fraudulent transactions using pattern recognition and anomaly detection.</div>
      <div class="project-tech"><span>Python</span><span>Scikit-learn</span><span>Pandas</span></div>
      <div class="project-media">
        <img src="https://github.com/user-attachments/assets/77125b73-66ed-4e04-8a8a-553b0cf13f9e" alt="Fraud Detection Results">
      </div>
      <a href="https://github.com/Snehaail11/frauddetection" class="project-link" target="_blank">View Project →</a>
    </div>

    <!-- Credit Card Fraud Detection (EMOJI) -->
    <div class="project-card">
      <div class="project-title"><i class="fas fa-credit-card"></i> Credit Card Fraud Detection</div>
      <div class="project-desc">Logistic Regression model to detect fraudulent credit card transactions from imbalanced dataset using under-sampling.</div>
      <div class="project-tech"><span>Python</span><span>Scikit-learn</span><span>Pandas</span><span>NumPy</span></div>
      <div class="emoji-media">
        💳⚠️🔍
      </div>
      <a href="https://github.com/Snehaail11/Snehaail11/blob/main/Credit_Card_Fraud_detection.ipynb" class="project-link" target="_blank">View Project →</a>
    </div>

    <!-- Sentiment Analysis (EMOJI) -->
    <div class="project-card">
      <div class="project-title"><i class="fas fa-brain"></i> News Sentiment Analysis</div>
      <div class="project-desc">Real-time news sentiment analysis using VADER, fetching Tesla-related articles via NewsAPI.</div>
      <div class="project-tech"><span>Python</span><span>NLTK</span><span>NewsAPI</span><span>Pandas</span></div>
      <div class="emoji-media">
        😊📰📈
      </div>
      <a href="https://github.com/Snehaail11/Snehaail11/blob/main/Sentiment_analysis.ipynb" class="project-link" target="_blank">View Project →</a>
    </div>

    <!-- Data Professional Survey -->
    <div class="project-card">
      <div class="project-title"><i class="fas fa-chart-pie"></i> Data Professional Survey</div>
      <div class="project-desc">Power BI dashboard analyzing global data professional trends, salary, tools, satisfaction.</div>
      <div class="project-tech"><span>Power BI</span><span>DAX</span></div>
      <div class="project-media">
        <iframe src="https://www.youtube.com/embed/zUEEZgokx6w" frameborder="0" allowfullscreen></iframe>
      </div>
      <a href="https://github.com/Snehaail11/surveypb" class="project-link" target="_blank">View Project →</a>
    </div>

    <!-- Bike Sales Analysis -->
    <div class="project-card">
      <div class="project-title"><i class="fas fa-bicycle"></i> Bike Sales Analysis</div>
      <div class="project-desc">Excel analysis with pivot tables, charts, and interactive dashboards.</div>
      <div class="project-tech"><span>Excel</span><span>Pivot Tables</span><span>Dashboards</span></div>
      <div class="project-media">
        <iframe src="https://www.youtube.com/embed/gSn6d0dLRUE" frameborder="0" allowfullscreen></iframe>
      </div>
      <a href="https://github.com/Snehaail11/bikesales" class="project-link" target="_blank">View Project →</a>
    </div>

    <!-- Shopping Trends Analysis (IMAGE) -->
    <div class="project-card">
      <div class="project-title"><i class="fas fa-shopping-cart"></i> Shopping Trends Analysis</div>
      <div class="project-desc">Analyzed customer purchasing behaviors and demographics using Python.</div>
      <div class="project-tech"><span>Python</span><span>Pandas</span><span>Matplotlib</span></div>
      <div class="project-media">
        <img src="https://github.com/user-attachments/assets/4d336141-6b06-4e81-b414-c631032cc40e" alt="Shopping Trends">
      </div>
      <a href="https://github.com/Snehaail11/AICTEP3" class="project-link" target="_blank">View Project →</a>
    </div>

    <!-- Airbnb Tableau Project -->
    <div class="project-card">
      <div class="project-title"><i class="fas fa-home"></i> Airbnb Tableau Dashboard</div>
      <div class="project-desc">Tableau dashboard analyzing Airbnb listings, pricing, availability trends.</div>
      <div class="project-tech"><span>Tableau</span><span>Data Visualization</span></div>
      <div class="project-media">
        <iframe src="https://www.youtube.com/embed/_Hqo05piwss" frameborder="0" allowfullscreen></iframe>
      </div>
      <a href="https://public.tableau.com/app/profile/sneha.ail/viz/ListingsTableauFullProject_17475792595120/Dashboard1" class="project-link" target="_blank">View Dashboard →</a>
    </div>

  </div>

  <!-- FREELANCE + CONTACT -->
  <div class="freelance-section">
    <h2 style="margin-top: 0; border-left: none; justify-content: center; padding-left: 0;">
      <i class="fas fa-handshake"></i> Open for Freelancing Gigs
    </h2>
    <p style="margin-bottom: 1rem;">AI solutions · Data consulting · Product prototyping · ML integration</p>
    <div class="contact-icons">
      <a href="mailto:snehaail1104@gmail.com" class="contact-icon"><i class="fas fa-envelope"></i> snehaail1104@gmail.com</a>
      <a href="https://linkedin.com/in/sneha-ail-584440205" target="_blank" class="contact-icon"><i class="fab fa-linkedin"></i> LinkedIn</a>
      <a href="https://github.com/Snehaail11" target="_blank" class="contact-icon"><i class="fab fa-github"></i> GitHub</a>
    </div>
  </div>

  <hr>
  <div style="text-align: center; font-size: 0.7rem; opacity: 0.6;">
    <i class="fas fa-code-branch"></i> building at intersection of AI + product · Let's collaborate
  </div>
</div>

</body>
</html>
