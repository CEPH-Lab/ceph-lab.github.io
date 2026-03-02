---
layout: default
title: Home
permalink: /
---
<style>
  /* Text Styling */
  .mission-text {
    font-size: 18px; 
    line-height: 1.7;
    color: #444;
    margin-bottom: 30px;
    margin-top: 20px;
  }
  
  .what-we-do-list {
    font-size: 18px;
    line-height: 1.7;
    color: #444;
    margin-bottom: 50px;
  }
  
  .what-we-do-list li {
    margin-bottom: 10px;
  }

  /* Modern, Sleek Section Headers */
  .section-header {
    font-size: 28px;
    text-transform: uppercase;
    letter-spacing: 2px;
    color: #508c96;
    font-weight: 700;
    margin-top: 50px;
    margin-bottom: 25px;
    display: flex;
    align-items: center;
    border: none;
  }
  
  .section-header::after {
    content: "";
    flex: 1;
    height: 1px;
    background: #e5e5e5;
    margin-left: 20px;
  }

  /* Elevated Card Accordion */
  .research-card {
    margin-bottom: 20px;
    background-color: #ffffff;
    border-radius: 8px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.04);
    border: 1px solid #f0f0f0;
    border-left: 6px solid #508c96;
    transition: all 0.3s ease;
  }
  
  .research-card:hover {
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
    transform: translateY(-2px); 
  }
  
  /* Clickable Header */
  .research-card summary {
    font-size: 20px;
    font-weight: 600;
    color: #2b2b2b;
    padding: 25px;
    cursor: pointer;
    list-style: none;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  /* Removes default triangle in Safari */
  .research-card summary::-webkit-details-marker {
    display: none;
  }
  
  /* Circular Animated Icon */
  .research-card summary::after {
    content: '+';
    font-family: monospace;
    font-size: 24px;
    line-height: 1;
    color: #fff;
    background-color: #508c96;
    width: 35px;
    height: 35px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: all 0.3s ease;
  }
  
  .research-card[open] summary::after {
    content: '−';
    background-color: #36636a;
    transform: rotate(180deg);
  }

  /* Text Content */
  .research-content {
    padding: 0 25px 30px 25px;
  }

  .research-text {
    line-height: 1.8;
    color: #555;
    margin: 0;
    font-size: 16px;
  }
</style>

<h2 class="section-header">Mission</h2>
<div class="mission-text">
  <p>Our mission is to advance the understanding of infectious disease dynamics through applied infectious
    disease epidemiology and mathematical modeling. By studying infectious disease outbreaks and pandemics and
    developing new tools, we generate actionable insights that inform public health decision-making and strengthen
    preparedness and response planning.</p>
</div>

<h2 class="section-header">What We Do</h2>
<div class="mission-text">
  <p>We study how infectious diseases spread and how outbreaks can be better prevented and controlled. Our lab:</p>
</div>
<ul class="what-we-do-list">
  <li>Uses mathematical modeling and applied infectious disease epidemiology to investigate disease dynamics.</li>
  <li>Develops tools to analyze, track, and forecast infectious disease outbreaks and pandemics.</li>
  <li>Produces actionable insights that support public health decision-making, preparedness, and response.</li>
</ul>

<h2 class="section-header">Research Areas</h2>

<details class="research-card">
  <summary>Forecasting of Respiratory Viral Diseases</summary>
  <div class="research-content">
    <p class="research-text">We develop mathematical models to forecast the trajectory of major respiratory pathogens,
    including COVID-19, Influenza (Flu), and Respiratory Syncytial Virus (RSV). Our forecasting models integrate
    real-time epidemiological data to provide early warnings and anticipate healthcare system burdens.</p>
  </div>
</details>

<details class="research-card">
  <summary>Intervention Assessment</summary>
  <div class="research-content">
    <p class="research-text">As active contributors to the Scenario Modeling Hub, we evaluate the potential impact
    of public health interventions against Respiratory Syncytial Virus (RSV) and Influenza (Flu). By simulating various
    scenarios, we assess the epidemiological impacts of pharmaceutical interventions, vaccination strategies, and 
    non-pharmaceutical measures.</p>
  </div>
</details>

<details class="research-card">
  <summary>Social Contact Patterns</summary>
  <div class="research-content">
    <p class="research-text">Human mixing behaviors are fundamental drivers of disease transmission. 
    We map detailed social contact patterns in the post-pandemic era to understand heterogeneous risk across 
    different socio-demographic groups. By identifying how, where, and when individuals interact, we can more 
    precisely model the spread of respiratory pathogens.</p>
  </div>
</details>

<details class="research-card">
  <summary>Multi-scale Modeling</summary>
  <div class="research-content">
    <p class="research-text">We build a data driven multi-scale frameworks, VIBES and IBES, to simulate disease
    transmission at multiple scales. These detailed Individual-Based Models (IBMs) integrate granular mobility,
    demographic, and behavioral data to capture the complex dynamics of epidemics from the individual interaction
    level up to the broader population level.</p>
  </div>
</details>

<details class="research-card" open>
  <summary>Forecasting of Mosquitoes</summary>
  <div class="research-content">
    <p class="research-text">These projects focus on forecasting vector mosquito population dynamics. 
    By integrating environmental, climatic, and ecological data, we predict periods of high vector abundance
    to inform proactive and highly targeted public health responses.</p>
  </div>
</details>

<details class="research-card">
  <summary>Mosquito Behavior</summary>
  <div class="research-content">
    <p class="research-text">Understanding the specific behaviors of vector mosquitoes is critical for mitigating
    outbreaks of diseases like dengue and Zika. This project examines mosquito diel (daily) activity patterns and
    behaviors in urban environments to optimize the timing and spatial distribution of vector control strategies.</p>
  </div>
</details>

