---
layout: default
title: Home
permalink: /
---
<style>
  .page-content {
    padding-bottom: 0 !important;
  }

  /* --- Hero Banner Styling --- */
  .hero {
    position: relative;
    height: 90vh; 
    width: 100vw;
    margin-left: calc(-50vw + 50%); 
    margin-top: -30px; 
    margin-bottom: 0px; /* Keeps the grid perfectly flush */
    background-image: linear-gradient(rgba(15, 32, 39, 0.6), rgba(32, 58, 67, 0.7)), url('/images/banner.png');
    background-size: cover;
    background-position: center;
    background-attachment: fixed; 
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
  }

  .hero h1 {
    font-size: 3.5rem;
    margin-bottom: 15px;
    letter-spacing: 1px;
    color: #ffffff;
    max-width: 1000px;
    padding: 0 20px;
  }

  .hero p {
    font-size: 1.5rem;
    font-weight: 300;
    margin-bottom: 40px;
    color: #e0f2f1;
    max-width: 800px;
    padding: 0 20px;
  }

  /* Bouncing Scroll Down Arrow */
  .scroll-down {
    display: flex; 
    justify-content: center;
    align-items: center;
    height: 50px; 
    width: 50px;
    margin-top: -20px; 
    text-decoration: none;
    animation: bounce 2s infinite;
    opacity: 0.6; 
    transition: opacity 0.3s ease;
  }

  .scroll-down:hover {
    opacity: 1; 
  }

  .scroll-down::after {
    content: '';
    display: block;
    width: 15px; 
    height: 15px; 
    border-bottom: 2px solid #42e8e0; 
    border-right: 2px solid #42e8e0; 
    transform: rotate(45deg); 
  }

  @keyframes bounce {
    0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
    40% { transform: translateY(-10px); }
    60% { transform: translateY(-5px); }
  }

  /* --- Feature Tiles Grid --- */
  .feature-tiles {
    display: grid;
    grid-template-columns: 1fr 1fr; /* Two equal columns */
    width: 100vw;
    margin-left: calc(-50vw + 50%);
    margin-top: 0; 
    margin-bottom: 0px;
    border-radius: 0; 
    overflow: hidden; 
  }

  .tile {
    padding: 60px 8%; 
    display: flex;
    flex-direction: column;
    justify-content: center;
    color: #ffffff;
  }

  /* Grid Positioning and Colors */
  .tile-mission { 
    background-color: #318287; 
    grid-column: 1; 
    grid-row: 1;
    justify-content: flex-start;
  } 
  
  .tile-what { 
    background-color: #1f5459; 
    grid-column: 1; 
    grid-row: 2;    
  }  
  
  .tile-about { 
    background-color: #112226; 
    grid-column: 2; 
    grid-row: 1 / span 2; 
    justify-content: flex-start;
  }

  /* Tile Typography */
  .tile-title {
    font-size: 24px;
    font-weight: 700;
    margin: 0 0 15px 0;
    color: #ffffff;
    border: none;
    text-transform: uppercase;
    letter-spacing: 1px;
  }
  
  .tile p {
    font-size: 16px;
    line-height: 1.7;
    margin: 0;
    color: rgba(255, 255, 255, 0.95);
  }

  .tile ul {
    padding-left: 20px;
    margin: 0;
    color: rgba(255, 255, 255, 0.95);
    font-size: 15px;
    line-height: 1.6;
  }

  .tile li {
    margin-bottom: 12px;
  }
  
  .tile li:last-child {
    margin-bottom: 0;
  }

  .tile-about p {
    font-size: 18px;
    line-height: 1.8;
  }

  /* --- Hiring Card --- */
  .opportunity-card {
    margin-top: 15px;
    margin-bottom: 20px;
    background-color: rgba(255, 255, 255, 0.05); /* Soft translucent white */
    border-radius: 8px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
    border: 1px solid rgba(255, 255, 255, 0.1); /* Subtle white outline */
    border-left: 6px solid #42e8e0; /* Pops against the navy background */
    transition: all 0.3s ease;
  }
  
  .opportunity-card:hover {
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.4);
    transform: translateY(-2px); 
    background-color: rgba(255, 255, 255, 0.08); /* Brightens slightly on hover */
  }

  .opportunity-title {
    font-size: 20px;
    font-weight: 600;
    color: #ffffff; /* White text for dark mode */
    padding: 25px 25px 15px 25px;
    margin: 0;
  }

  .opportunity-content {
    padding: 0 25px 30px 25px;
  }

  .opportunity-text {
    line-height: 1.7;
    color: rgba(255, 255, 255, 0.85); /* Legible off-white text */
    margin: 0 0 15px 0;
    font-size: 15px;
  }

  /* Buttons */
  .apply-btn {
    display: inline-block;
    background-color: #508c96;
    color: #ffffff !important;
    padding: 10px 22px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: 600;
    font-size: 15px;
    transition: background-color 0.2s ease;
  }
  
  .apply-btn:hover {
    background-color: #42e8e0; /* Hover changes to the bright cyan */
    color: #0f2027 !important; /* Text turns dark on hover for contrast */
    text-decoration: none;
  }

  /* --- Mobile Responsiveness --- */
  @media screen and (max-width: 900px) {
    .feature-tiles {
      grid-template-columns: 1fr; /* Stacks the grid on mobile */
    }
    .tile-about {
      grid-column: 1; 
      grid-row: auto; 
    }
  }

  @media screen and (max-width: 768px) {
    .hero h1 {
      font-size: 2rem; 
      margin-top: 20px;
    }
    .hero p {
      font-size: 1.1rem; 
      margin-bottom: 20px;
    }
    .scroll-down {
      height: 40px; 
      width: 40px;
    }
    .tile {
      padding: 40px 5%;
    }
  }
</style>

<div class="hero">
  <h1>Where Ideas Inspire Action</h1>
  <p>We are committed to advancing the understanding of epidemic spread and informing public health decision-making</p>
  <a href="#mission" class="scroll-down" aria-label="Scroll to Mission"></a>
</div>

<div class="feature-tiles">
  
  <div class="tile tile-mission">
    <div id="mission"></div> 
    <h3 class="tile-title">Mission</h3>
    <p>Our mission at the Laboratory for Computational Epidemiology and Public Health (CEPH Lab) is to advance the
    understanding of infectious disease epidemiology and provide actionable insights to inform public health policy.</p>
  </div>

  <div class="tile tile-what">
    <h3 class="tile-title">What we do</h3>
    <ul>
      <li>Develop mathematical and computational modeling tools that simulate infectious disease transmission
        to investigate epidemic spread</li>
      <li>Apply statistical modeling to identify the socio-economic, behavioral, and environmental determinants
        of the epidemiology of infectious diseases and the ecology of their vectors</li>
      <li>Conduct model-based evaluations of the effectiveness of public health interventions to inform public
        health decision-making</li>
      <li>Forecast and nowcast infectious disease dynamics and vector populations to enhance public health
        situational awareness</li>
    </ul>
    <div style="margin-top: 25px;">
      <a href="{{ '/research/' | relative_url }}" class="apply-btn" style="background-color: #ffffff;
        color: #36636a !important;">Explore Our Research</a>
    </div>
  </div>

  <div class="tile tile-about">
    <h3 class="tile-title" style="color: #42e8e0;">About Us</h3>
    <p>The laboratory is led by Marco Ajelli and is affiliated to the Department of Epidemiology and Biostatistics
    at the Indiana University School of Public Health - Bloomington.</p>
    
<h3 class="tile-title" style="margin-top: 50px; color: #42e8e0;">Join Us</h3>
    
<div class="opportunity-card">
<h3 class="opportunity-title">We are Hiring</h3>
<div class="opportunity-content">
<p class="opportunity-text">We are hiring a postdoctoral fellow in Infectious Disease modeling. We seek candidates
with a doctoral degree in a quantitative field (e.g., Mathematics, Physics, Computer Science, or a related discipline).
Candidates should be passionate about understanding the mechanisms driving epidemic spread, designing mathematical
models, and building computational engines. The work will primarily focus on respiratory infectious diseases
(e.g., COVID-19, influenza, RSV) and mosquito-borne diseases but may pivot to public health emergencies.</p>
<p class="opportunity-text" style="font-style: italic; color: #42e8e0;">For inquiries regarding open positions,
please get in touch with Dr. Ajelli directly with your CV.</p>
        
<div style="display: flex; gap: 15px; flex-wrap: wrap; margin-top: 20px;">
<a href="mailto:majelli@iu.edu?subject=Postdoc Inquiry - CEPH Lab" class="apply-btn">Email Dr. Ajelli</a>
<a href="https://indiana.peopleadmin.com/postings/32436" target="_blank" class="apply-btn">Current Openings</a>
</div>
</div>
</div>
</div>

</div>