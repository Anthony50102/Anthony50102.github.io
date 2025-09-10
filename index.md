---
layout: default
title: Anthony Poole - Software Engineer & Researcher
permalink: /
---

<style>
  /* Override Cayman theme's large header */
  .page-header {
    padding: 2rem 1rem !important;
    background-image: linear-gradient(120deg, #155799, #159957) !important;
  }
  
  .project-name {
    font-size: 2.25rem !important;
  }
  
  .project-tagline {
    font-size: 1.15rem !important;
    opacity: 0.9;
  }
  
  /* Main content styling */
  .main-content {
    max-width: 64rem;
    margin: 0 auto;
  }
  
  .hero-section {
    display: flex;
    align-items: center;
    gap: 3rem;
    margin-bottom: 3rem;
    padding-top: 2rem;
  }
  
  .profile-image {
    width: 220px;
    height: 220px;
    border-radius: 12px;
    object-fit: cover;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15);
    transition: transform 0.3s ease;
  }
  
  .profile-image:hover {
    transform: translateY(-4px);
  }
  
  .hero-content h1 {
    margin-top: 0;
    font-size: 2.5rem;
    color: #155799;
  }
  
  .hero-content .subtitle {
    font-size: 1.25rem;
    color: #666;
    margin-bottom: 1rem;
  }
  
  .quick-links {
    display: flex;
    gap: 1rem;
    margin-top: 1.5rem;
  }
  
  .quick-links a {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.5rem 1rem;
    background-color: #f5f5f5;
    border-radius: 6px;
    text-decoration: none;
    color: #333;
    transition: all 0.3s ease;
  }
  
  .quick-links a:hover {
    background-color: #155799;
    color: white;
    transform: translateY(-2px);
  }
  
  .section {
    margin-bottom: 3rem;
  }
  
  .section h2 {
    color: #155799;
    border-bottom: 3px solid #159957;
    padding-bottom: 0.5rem;
    margin-bottom: 1.5rem;
    font-size: 1.75rem;
  }
  
  .experience-item, .education-item {
    margin-bottom: 2rem;
    padding-left: 1rem;
    border-left: 3px solid #e1e4e8;
  }
  
  .experience-item h3, .education-item h3 {
    margin-top: 0;
    color: #333;
  }
  
  .date {
    color: #666;
    font-style: italic;
    font-size: 0.95rem;
  }
  
  .tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-top: 1rem;
  }
  
  .tag {
    background-color: #159957;
    color: white;
    padding: 0.35rem 0.85rem;
    border-radius: 20px;
    font-size: 0.875rem;
    transition: all 0.3s ease;
  }
  
  .tag:hover {
    background-color: #155799;
    transform: scale(1.05);
  }
  
  .research-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
    margin-top: 1.5rem;
  }
  
  .research-card {
    background-color: #f8f9fa;
    padding: 1.5rem;
    border-radius: 8px;
    border-left: 4px solid #159957;
  }
  
  .research-card h4 {
    margin-top: 0;
    color: #155799;
  }
  
  .contact-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1rem;
    margin-top: 1.5rem;
  }
  
  .contact-item {
    display: flex;
    align-items: center;
    gap: 0.75rem;
    padding: 1rem;
    background-color: #f5f5f5;
    border-radius: 6px;
    text-decoration: none;
    color: #333;
    transition: all 0.3s ease;
  }
  
  .contact-item:hover {
    background-color: #e9ecef;
    transform: translateX(4px);
  }
  
  @media (max-width: 768px) {
    .hero-section {
      flex-direction: column;
      text-align: center;
    }
    
    .quick-links {
      justify-content: center;
      flex-wrap: wrap;
    }
    
    .hero-content h1 {
      font-size: 2rem;
    }
  }
</style>

<div class="hero-section">
  <img src="IMG_0572.jpeg" alt="Anthony Poole" class="profile-image">
  <div class="hero-content">
    <h1>Hi, I'm Anthony! 👋</h1>
    <p class="subtitle">Software Engineer at Microsoft | Researcher in Applied Math</p>
    <p>I enjoy working at the intersection of math, physics and computer science. Currently developing LLM-powered tools for code security at Microsoft while pursuing research in probabilistic modeling and chaotic systems.</p>
    <div class="quick-links">
      <a href="mailto:tonypp@utexas.edu">📧 Email</a>
      <a href="https://www.linkedin.com/in/anthony-poole-079548206/">🔗 LinkedIn</a>
      <a href="https://github.com/Anthony50102">🐙 GitHub</a>
    </div>
  </div>
</div>

<div class="section">
  <h2>Experience</h2>
  
  <div class="experience-item">
    <h3>Software Engineer - Microsoft</h3>
    <p class="date">Present</p>
    <p>Building internal security tools that leverage large language models to identify vulnerabilities and insecure code patterns across Microsoft's extensive codebase. Focused on improving code security through automated analysis and intelligent pattern detection.</p>
  </div>
  
  <div class="experience-item">
    <h3>Data Science Intern - Kodiak Robotics</h3>
    <p class="date">Previous Role</p>
    <p>Developed Kodiak's first high-level reasoning model, integrating data inputs from across the autonomous vehicle stack to create a unified understanding of vehicle state and environment.</p>
  </div>

  <div class="experience-item">
    <h3>Machine Learning Intern - Advanced Micro Devices</h3>
    <p class="date">Previous Role</p>
    <p>Developed unsupervised computer vision and image processing models and pipelines for non-destructive damage analysis of mi300 chips in production.</p>
  </div>

  <div class="experience-item">
    <h3>Software Engineer Intern - Applied Research Laboratories</h3>
    <p class="date">Previous Role</p>
    <p>Developed navigation and perception software for autonomous submarines.</p>
  </div>
</div>

<div class="section">
  <h2>Education</h2>
  
  <div class="education-item">
    <h3>University of Texas at Austin</h3>
    <p><strong>B.S. in Physics | Minor in Computational Science</strong></p>
    <p class="date">May 2025</p>
    <p>Favorite Courses: Quantum information science, distributed systems, unconventional computation</p>
  </div>
</div>

<div class="section">
  <h2>Research</h2>
  
  <div class="research-grid">
    <div class="research-card">
      <h4>Probabilistic Reduced Order Models</h4>
      <p>Collaborating with the <a href="https://kiwi.oden.utexas.edu">Willcox Lab</a> on developing efficient computational methods for complex systems using probabilistic approaches.</p>
    </div>
    
    <div class="research-card">
      <h4>Deep Learning for Chaotic Systems</h4>
      <p>Working with <a href="https://math.vt.edu/people/faculty/farcas-ionut-gabriel.html">Ionut Farcaș</a> on neural network approaches for modeling ergodic and chaotic dynamics, with applications in turbulence modeling.</p>
    </div>

    <!--
    <div class="research-card">
      <h4>AI for Code Security</h4>
      <p>Exploring advanced LLM applications in automated vulnerability detection and developing best practices for secure coding at scale.</p>
    </div>
    -->
  </div>
</div>

<div class="section">
  <h2>Technical Skills</h2>
  
  <h3>Core Competencies</h3>
  <div class="tags">
    <span class="tag">Machine Learning</span>
    <span class="tag">Scientific Computing</span>
    <span class="tag">Security Analysis</span>
    <span class="tag">Data Science</span>
    <span class="tag">Inferential Statistics</span>
  </div>
  
  <h3>Languages & Tools</h3>
  <div class="tags">
    <span class="tag">Python</span>
    <span class="tag">C++</span>
    <span class="tag">Java</span>
    <span class="tag">PyTorch</span>
    <span class="tag">JAX</span>
    <span class="tag">High Performance Computing</span>
  </div>
  
  <h3>Research Areas</h3>
  <div class="tags">
    <span class="tag">Turbulence Modeling</span>
    <span class="tag">Chaotic Systems</span>
    <span class="tag">Reduced Order Modeling</span>
    <span class="tag">Bayesian Methods</span>
    <span class="tag">SciML</span>
  </div>
</div>

<div class="section">
  <h2>Let's Connect</h2>
  <p>I'm always interested in discussing research collaborations, software, or really anything interesting!.</p>
  
  <div class="contact-grid">
    <a href="mailto:tonypp@utexas.edu" class="contact-item">
      <span>📧</span>
      <span>tonypp@utexas.edu</span>
    </a>
    <a href="https://www.linkedin.com/in/anthony-poole-079548206/" class="contact-item">
      <span>🔗</span>
      <span>LinkedIn Profile</span>
    </a>
    <a href="https://github.com/Anthony50102" class="contact-item">
      <span>🐙</span>
      <span>GitHub: Anthony50102</span>
    </a>
  </div>
</div>
