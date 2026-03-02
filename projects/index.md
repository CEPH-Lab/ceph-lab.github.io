---
layout: default
title: Projects
permalink: /projects/
---

<style>
  .intro-text {
    font-size: 18px; 
    line-height: 1.7;
    color: #444;
    margin-bottom: 50px;
    margin-top: 40px;
  }

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

  /* Static Directory Card */
  .project-card {
    margin-bottom: 20px;
    background-color: #ffffff;
    border-radius: 8px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.04);
    border: 1px solid #f0f0f0;
    border-left: 6px solid #508c96;
    padding: 25px;
    transition: all 0.3s ease;
  }
  
  .project-card:hover {
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
    transform: translateY(-2px); 
  }
  
  .project-title {
    font-size: 22px;
    font-weight: 600;
    color: #2b2b2b;
    margin: 0 0 10px 0;
  }

  .project-summary {
    line-height: 1.7;
    color: #555;
    margin: 0 0 20px 0;
    font-size: 16px;
  }
  
  /* Link Button to the Sub-Page */
  .read-more-btn {
    display: inline-block;
    background-color: #508c96;
    color: #ffffff !important;
    padding: 8px 18px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: 600;
    font-size: 14px;
    transition: background-color 0.2s ease;
  }
  
  .read-more-btn:hover {
    background-color: #36636a;
    text-decoration: none;
  }
</style>

<div class="intro-text">
  <p>Our lab focuses on several key areas of infectious disease dynamics. Select a project below to learn more about our methodologies, models, and findings.</p>
</div>

<h2 class="section-header">Multi-scale Modeling</h2>

<div class="project-card">
  <h3 class="project-title">VIBES</h3>
  <p class="project-summary">A high-resolution Individual-Based Model (IBM) framework designed to simulate disease transmission at multiple scales by integrating granular mobility, demographic, and behavioral data.</p>
  
  <a href="{{ '/projects/vibes/' | relative_url }}" class="read-more-btn">Read More</a>
</div>

<div class="project-card">
  <h3 class="project-title">IBES</h3>
  <p class="project-summary">A brief 1-2 sentence summary of what IBES does goes here to entice the reader to click.</p>
  <a href="#" class="read-more-btn">Read More</a>
</div>

<h2 class="section-header">Intervention Assessment</h2>

<div class="project-card">
  <h3 class="project-title">Scenario Modeling Hub (RSV & Flu)</h3>
  <p class="project-summary">Evaluating the potential impact of public health interventions and vaccination strategies through rigorous scenario simulation.</p>
  <a href="#" class="read-more-btn">Read More</a>
</div>