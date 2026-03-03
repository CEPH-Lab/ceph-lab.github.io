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

<img src="/images/banner.png" width="100%">

<h2 class="section-header">Mission</h2>
<div class="mission-text">
  <p>Our mission is to advance the understanding of infectious disease dynamics through applied infectious
    disease epidemiology and mathematical modeling. By studying infectious disease outbreaks and
    developing modeling tools, we provide actionable insights that inform public health decision-making and strengthen
    preparedness and response planning.</p>
</div>

<h2 class="section-header">What We Do</h2>
<div class="mission-text">
</div>
<ul class="what-we-do-list">
  <li>Develop mathematical and computational modeling tools that simulate infectious disease transmission
    to investigate epidemic spread</li>
  <li>Forecast population and infectious disease dynamics to provide situational awareness</li>
  <li>Conduct model-based evaluations of the effectiveness of public health interventions to inform public health
    decision-making</li>
</ul>

<h2 class="section-header">Research Areas</h2>

<details class="research-card">
  <summary>Forecasting of Respiratory Viral Diseases</summary>
  <div class="research-content">
    <p class="research-text">We develop mathematical models to forecast the trajectory of major respiratory pathogens,
    including COVID-19, Influenza (Flu), and Respiratory Syncytial Virus (RSV). Our forecasting models integrate
    real-time epidemiological data to provide situational awareness and anticipate healthcare system burdens.</p>
  </div>
</details>

<details class="research-card">
  <summary>Intervention Assessment</summary>
  <div class="research-content">
    <p class="research-text">We evaluate the potential impact of public health interventions against respiratory
    infectious diseases through the development of mathematical models and participating in the Scenario 
    Modeling Hub(SMH) for Respiratory Syncytial Virus (RSV), Influenza (Flu) and Pandemic cryptic phase.
    By simulating various scenarios, we assess the epidemiological impacts of pharmaceutical interventions,
    vaccination strategies, and non-pharmaceutical measures.</p>
  </div>
</details>

<details class="research-card">
  <summary>Social Contact Patterns</summary>
  <div class="research-content">
    <p class="research-text">Social mixing patterns are fundamental drivers of respiratory pathogen transmission. 
    We leveraged detailed social contact patterns to understand heterogeneous risk across different socio-demographic
    groups. By identifying how, where, when and with whom individuals interact, we can more 
    precisely model the spread of respiratory infectious diseases.</p>
  </div>
</details>

<details class="research-card">
  <summary>Multi-scale Modeling</summary>
  <div class="research-content">
    <p class="research-text">As disease spread is an inherently multi-scale process, we build a data driven,
    multi-scale framework to simulate respiratory pathogen transmission at within-host and between-hosts scales.
    Our multi-scale framework integrates granular mobility, demographic, and behavioral data to capture
    the complex dynamics of epidemic spread at the individual and population level.</p>
  </div>
</details>

<details class="research-card">
  <summary>Forecasting of Mosquitoes</summary>
  <div class="research-content">
    <p class="research-text">These projects focus on forecasting mosquito vector population dynamics. 
    By integrating environmental and ecological data, we forecast mosquito abundance
    to provide situational awareness and inform proactive and highly targeted public health response.</p>
  </div>
</details>

<details class="research-card">
  <summary>Mosquito Behavior</summary>
  <div class="research-content">
    <p class="research-text">Understanding the specific behaviors of mosquito vectors is critical for mitigating
    outbreaks of arboviral diseases like dengue and Zika. We examine mosquito diel (daily) activity
    patterns and behaviors in urban environments to evaluate the effectiveness of vector control strategies.</p>
  </div>
</details>

