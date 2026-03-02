---
layout: page
title: Home
permalink: /
---
<style>
  /* Mission Text Styling */
  .mission-text {
    font-size: 18px; 
    line-height: 1.7;
    color: #444;
    margin-bottom: 50px;
    margin-top: 20px;
    max-width: 900px;
  }

  /* Modern, Sleek Section Headers */
  .section-header {
    font-size: 14px;
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

<h2 class="section-header">Our Mission</h2>
<div class="mission-text">
  <p>The Laboratory for Computational Epidemiology and Public Health (CEPH) utilizes mathematical and 
    computational modeling to advance the understanding of infectious disease dynamics and provide
    actionable insights to inform infectious disease outbreak preparedness and response planning.</p>
</div>

<h2 class="section-header">Research Areas</h2>

<details class="research-card">
  <summary>Respiratory Viruses Forecasting</summary>
  <div class="research-content">
    <p class="research-text">Add information about the forecasting of COVID-19, Flu and RSV.</p>
  </div>
</details>

<details class="research-card">
  <summary>Intervention Assessment</summary>
  <div class="research-content">
    <p class="research-text">Add information about Scenario Modeling Hub Projects
    on Respiratory Syncytial Virus (RSV) and Influenza (Flu).</p>
  </div>
</details>

<details class="research-card">
  <summary>Social Contact Patterns</summary>
  <div class="research-content">
    <p class="research-text">Add information about Contact Pattern paper and heterogeneous risk</p>
  </div>
</details>

<details class="research-card">
  <summary>Multi-scale Modeling</summary>
  <div class="research-content">
    <p class="research-text">Add information about VIBES and IBES here</p>
  </div>
</details>

<details class="research-card" open>
  <summary>Mosquito Forecasting</summary>
  <div class="research-content">
    <p class="research-text">Add information about Utkarsh and Katie's project</p>
  </div>
</details>

<details class="research-card">
  <summary>Mosquito Behavior</summary>
  <div class="research-content">
    <p class="research-text">Add information about Snigdha's project</p>
  </div>
</details>

