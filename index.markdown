---
layout: default
title: Home
---

<style>
.intro {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  text-align: justify;
  margin-bottom: 3rem;
  padding: 2rem 0;
}

.intro-text {
  flex: 1;
  min-width: 280px;
}

.intro img {
  max-width: 200px;
  width: 100%;
  height: auto;
  margin-right: 2rem;
  margin-bottom: 1rem;
  padding: 1rem;
  border-radius: 50%;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

@media screen and (min-width: 768px) {
  .intro img {
    max-width: 250px;
  }
}

@media screen and (max-width: 768px) {
  .intro {
    flex-direction: column;
    text-align: left;
  }
  
  .intro img {
    margin: 0 auto 1.5rem;
    max-width: 180px;
  }
}

.profile-section {
  margin: 3rem 0;
  padding: 2rem;
  background: #f8f9fa;
  border-radius: 8px;
  border-left: 4px solid #3498db;
}

@media screen and (max-width: 768px) {
  .profile-section {
    padding: 1.5rem;
    margin: 2rem 0;
  }
}

@media screen and (max-width: 480px) {
  .profile-section {
    padding: 1rem;
    margin: 1.5rem 0;
  }
}

.profile-section h2 {
  color: #2c3e50;
  margin-top: 0;
  border-bottom: 2px solid #e0e0e0;
  padding-bottom: 0.5rem;
}

.profile-section h3 {
  color: #34495e;
  margin-top: 1.5rem;
  margin-bottom: 0.5rem;
}

.profile-section ul {
  margin: 0.5rem 0;
  padding-left: 1.5rem;
}

.profile-section li {
  margin: 0.5rem 0;
}

.contact-links {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  margin-top: 1rem;
}

.contact-links a {
  padding: 0.5rem 1rem;
  background: #3498db;
  color: white;
  text-decoration: none;
  border-radius: 4px;
  transition: background 0.3s ease;
}

.contact-links a:hover {
  background: #2980b9;
}

@media screen and (max-width: 480px) {
  .contact-links,
  .research-links {
    flex-direction: column;
  }
  
  .contact-links a,
  .research-links a {
    width: 100%;
    text-align: center;
  }
}

.research-links {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  margin-top: 1rem;
}

.research-links a {
  color: #3498db;
  text-decoration: none;
  padding: 0.3rem 0.8rem;
  border: 1px solid #3498db;
  border-radius: 4px;
  transition: all 0.3s ease;
}

.research-links a:hover {
  background: #3498db;
  color: white;
}
</style>

  <div class="intro">
    <div class="intro-text">
    <p>I am a Vice President at Intesa Sanpaolo with a Ph.D. in Artificial Intelligence and over nine years of experience in quantitative finance, trading strategy development, and AI innovation. I specialize in developing systematic investment strategies powered by advanced machine learning techniques, including deep learning and reinforcement learning. As a CAIA charterholder, I combine hands-on trading experience with rigorous quantitative research to deliver institutional-grade trading systems that generate alpha while managing risk effectively.</p>
    <p>My work bridges cutting-edge academic research with practical applications in quantitative finance, driving digital transformation and data-driven decision-making in financial institutions. My research spans <a href="./research/">AI research</a>, as well as <a href="./space-economy/">space economy research</a>, reflecting a strategic approach to applying quantitative methods to complex economic systems.</p>
    </div>
          <img src="/images/me_round.png" alt="Profile Picture" />
  </div>

<div class="profile-section">
  <h2>Professional Experience</h2>
  <h3>2025 - Present</h3>
  <p><strong>Vice President, Cross Asset Systematic Trading</strong> — Intesa Sanpaolo IMICIB, Milan</p>
  <ul>
    <li>Scaling-up systematic FX strategies by upgrading strategies and improving execution</li>
    <li>Supervising build-up of systematic futures trading infrastructure</li>
  </ul>

  <h3>2022 - 2025</h3>
  <p><strong>Vice President, AI Investments</strong> — Intesa Sanpaolo IMICIB, Milan</p>
  <ul>
    <li>Conducting quantitative research and innovation on AI-driven FX and futures trading strategies</li>
    <li>Translating machine learning research into production-grade trading systems</li>
    <li>Supervising model implementation and performance oversight</li>
    <li>Driving the firm's strategic engagement in AI in finance, contributing as author, reviewer and organizer for international conferences</li>
  </ul>
  
  <h3>2018 - 2022</h3>
  <p><strong>Associate, XVA Management</strong> — Intesa Sanpaolo IMICIB, Milan</p>
  <ul>
    <li>Pricing the XVAs of derivatives and hedging the XVA book with macro trading tilt</li>
    <li>Conducting quantitative research and academic research as a doctoral student</li>
    <li>Job rotation 2020 - Epsilon SGR Asset Management: quantitative investing</li>
    <li>Job rotation 2019 - Intesa Sanpaolo: credit flow trading</li>
  </ul>
  
  <h3>2016 - 2018</h3>
  <p><strong>Analyst, XVA Management</strong> — Banca IMI, Milan</p>
  <ul>
    <li>Pricing the XVAs of derivatives and hedging the XVA book</li>
    <li>Working closely with sales, trading, structuring and risk teams to structure derivatives for clients</li>
  </ul>
  
  <h3>Summer 2015</h3>
  <p><strong>Intern</strong> — AMS (Alpha Magnetic Spectrometer), CERN, Geneva</p>
  <ul>
    <li>Analyzing data from AMS under the supervision of Nobel prize winner Samuel C. Ting</li>
    <li>Coordinated with NASA and research teams to ensure data integrity and mission continuity on the ISS</li>
  </ul>
</div>

<div class="profile-section">
  <h2>Education & Credentials</h2>
  
  <h3>2024 - 2025</h3>
  <p><strong>Scuola Politica - Vivere nella comunità</strong></p>
  <ul>
    <li>Coordinator of the project work: <em>Alfabetizzazione dei giovani in Italia, i nuovi progetti economico-finanziari</em></li>
  </ul>
  
  <h3>2018 - 2022</h3>
  <p><strong>Ph.D. in Artificial Intelligence</strong> — Politecnico di Milano</p>
  <ul>
    <li>Focus on reinforcement learning, online planning, bandits, online convex optimization</li>
    <li>Applications: quantitative trading, optimal execution, market making, hedging, portfolio optimization</li>
  </ul>
  
  <h3>2017 - 2018</h3>
  <p><strong>Executive Master in Finance</strong> — SDA Bocconi, Milan</p>
  <ul>
    <li>Specialized in advanced financial topics with a focus on banking transformation and leadership</li>
  </ul>
  
  <h3>2012 - 2016</h3>
  <p><strong>Master of Science in Mathematics</strong> — Imperial College London, First Class Honours</p>
  <ul>
    <li>Nominated Secretary of the Erasmus Society and External Relations Officer of the Italian Society</li>
    <li>Selected for Microfinance Tanzania, Mash Foundation; volunteered by advising local businesses</li>
  </ul>
  
  <h3>2014 - 2015</h3>
  <p><strong>Exchange Year</strong> — EPFL, Lausanne, Switzerland (Swiss-European Mobility Program)</p>
  <ul>
    <li>Engaged in Harvard World MUN (Model United Nations) debate, Seoul</li>
  </ul>
  
  <h3>Professional Credentials</h3>
  <ul>
    <li><strong>CAIA Charterholder</strong> — Chartered Alternative Investment Analyst</li>
  </ul>
</div>

<div class="profile-section">
  <h2>Research & Publications</h2>
  <p>My research has been applied in production trading systems and has contributed to the development of systematic trading strategies. I have published extensively in top-tier conferences and journals, with work spanning:</p>
  <ul>
    <li>Reinforcement learning for trading and hedging</li>
    <li>Market making and optimal execution strategies</li>
    <li>Online learning and optimization for portfolio management</li>
    <li>Space economy economic modeling and analysis</li>
  </ul>
  <div class="research-links">
    <a href="./publications/">View Publications</a>
    <a href="https://scholar.google.it/citations?user=gVKVhiwAAAAJ&hl=en" target="_blank">Google Scholar</a>
    <a href="https://www.researchgate.net/profile/Edoardo-Vittori" target="_blank">ResearchGate</a>
    <a href="https://dl.acm.org/profile/99659892125" target="_blank">ACM Profile</a>
  </div>
</div>

<div class="profile-section">
  <h2>Connect</h2>
  <p>I welcome opportunities for collaboration, speaking engagements, and consulting. Feel free to reach out through any of the channels below.</p>
  <div class="contact-links">
    <a href="{{ site.url }}/downloads/Edoardo_Vittori_CV.pdf">Download CV</a>
    <a href="https://www.linkedin.com/in/edoardo-vittori/" target="_blank">LinkedIn</a>
    <a href="mailto:edoardo.vittori@polimi.it">Email</a>
  </div>
</div>
