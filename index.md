---
layout: default
title: Anthony Poole - Software Engineer & Researcher
permalink: /
---

<style>
  /* Hide Cayman theme header — hero section below covers it */
  .page-header {
    display: none !important;
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
  <h2>Research & Publications</h2>
  <p>Research assistant at the <a href="https://kiwi.oden.utexas.edu">Willcox Lab</a> and with <a href="https://math.vt.edu/people/faculty/farcas-ionut-gabriel.html">Ionut Farcaș</a> at the Oden Institute, UT Austin (Oct 2023 — Present).</p>
  
  <div class="research-grid">
    <div class="research-card">
      <h4><a href="https://arxiv.org/html/2602.04287v1">Convolution Operator Network for Forward and Inverse Problems (FI-Conv): Application to Plasma Turbulence Simulations</a></h4>
      <p>Xingzhuo Chen, <strong>Anthony Poole</strong>, Ionut Farcas, David Hatch, Ulisses Braga-Neto</p>
      <p class="date">Submitted to Journal of Computational Physics · <a href="https://arxiv.org/html/2602.04287v1">arXiv</a></p>
    </div>

    <div class="research-card">
      <h4>Short-Term Forecasting vs Long-Term Statistical Fidelity in Learned Turbulent Systems</h4>
      <p><strong>Anthony Poole</strong>, Ionut Farcas et al.</p>
      <p class="date">Submitted to Journal of Computational Physics · email for pre-print</p>
    </div>

    <div class="research-card">
      <h4>Probabilistic Scientific Machine Learning via Bayesian Model Reduction</h4>
      <p><strong>Anthony Poole</strong>, Anirban Choudary, Karen Willcox</p>
      <p class="date">In progress · email for pre-print</p>
    </div>
  </div>
</div>

<div class="section">
  <h2>Talks & Conferences</h2>

  <div class="experience-item">
    <h3>Microelectronics US — Speaker</h3>
    <p class="date">Upcoming</p>
    <p>Invited talk on digital twin technology and virtual prototyping.</p>
  </div>

  <div class="experience-item">
    <h3>IPAM Workshop IV: Multi-Fidelity Methods for Robust Optimization and Real-Time Control of Fusion Processes — UCLA</h3>
    <p class="date">May 18–22, 2026</p>
    <p>Attendee.</p>
  </div>
</div>

<div class="section">
  <h2>Experience</h2>
  
  <div class="experience-item">
    <h3>Software Engineer - Microsoft</h3>
    <p class="date">June 2025 — Present · Redmond, WA</p>
    <p>Architected the AI agent harness and MCP for Microsoft's Code Analysis Platform, enabling automated vulnerability detection and fix generation. Built an A/B testing framework for evaluating agent configurations, improving fix quality by ~350%. Owned the platform's data pipeline using Databricks, Spark, and dbt—cutting processing time by 500×.</p>
  </div>

  <div class="experience-item">
    <h3>Software Engineer Intern - Microsoft</h3>
    <p class="date">May 2024 — Aug 2024 · Redmond, WA</p>
    <p>Designed a code understanding model enabling function-level search across Microsoft's codebase in multiple languages (92% on internal benchmarks). Built an advanced RAG system for security researchers, achieving 80% adoption and reducing average vulnerability research time by 60%.</p>
  </div>
  
  <div class="experience-item">
    <h3>Data Science Intern - Kodiak Robotics</h3>
    <p class="date">Jan 2024 — May 2024 · Mountain View, CA</p>
    <p>Built an Operational Design Domain model using data fusion, ensemble methods, and deep learning CV to classify in real time whether the AV was operating within its design envelope. Advanced the safety case through novel Bayesian statistical models informing engineering priorities.</p>
  </div>

  <div class="experience-item">
    <h3>Machine Learning Engineer Co-Op - AMD</h3>
    <p class="date">Aug 2023 — Dec 2023 · Austin, TX</p>
    <p>Designed an unsupervised image segmentation algorithm to quantify TIM delamination, reducing analysis error by >10%. Built a C++ Python package for geometric analytics, improving speed by >5,000× and adopted by ~20 engineers.</p>
  </div>

  <div class="experience-item">
    <h3>Software Engineer Intern - Applied Research Laboratories</h3>
    <p class="date">May 2023 — Aug 2023 · Austin, TX</p>
    <p>Distilled U-Net and SAM segmentation models into smaller architectures for seafloor imaging, improving submarine battery life by 15% without sacrificing accuracy.</p>
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
