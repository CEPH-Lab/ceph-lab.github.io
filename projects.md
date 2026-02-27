---
layout: page
title: Projects
permalink: /projects/
---

<style>
  .intro-text {
    font-size: 18px;
    line-height: 1.7;
    color: #444;
    margin-bottom: 60px;
    margin-top: 30px;
    max-width: 900px;
  }

  /* Section Headers */
  .research-area {
    font-size: 14px;
    text-transform: uppercase;
    letter-spacing: 2px;
    color: #508c96;
    font-weight: 700;
    margin-top: 60px;
    margin-bottom: 25px;
    display: flex;
    align-items: center;
    border: none;
  }
  
  .research-area::after {
    content: "";
    flex: 1;
    height: 1px;
    background: #e5e5e5;
    margin-left: 20px;
  }

  /* Card design */
  .project-dropdown {
    margin-bottom: 20px;
    background-color: #ffffff;
    border-radius: 8px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.04);
    border: 1px solid #f0f0f0;
    border-left: 6px solid #508c96;
    transition: all 0.3s ease;
  }
  
  .project-dropdown:hover {
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
    transform: translateY(-2px); /* Lifts the card on hover */
  }
  
  /* Clickable Header */
  .project-dropdown summary {
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
  .project-dropdown summary::-webkit-details-marker {
    display: none;
  }
  
  /* Circular Animated Icon */
  .project-dropdown summary::after {
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
  
  .project-dropdown[open] summary::after {
    content: '−';
    background-color: #36636a;
    transform: rotate(180deg);
  }

  /* Text Content */
  .project-content {
    padding: 0 25px 30px 25px;
  }

  .project-text {
    line-height: 1.8;
    color: #555;
    margin: 0;
    font-size: 16px;
  }
</style>

<div class="intro-text">
  <p>The Laboratory for Computational Epidemiology and Public Health (CEPH) utilizes mathematical and computational modeling to understand the transmission dynamics of infectious diseases. Our projects aim to evaluate the impact of human behavior, socio-demographic factors, and public health interventions to inform policy and epidemic preparedness.</p>
</div>

<h2 class="research-area">Respiratory Viruses</h2>

<details class="project-dropdown" open>
  <summary>Within and between-hosts multiscale modeling: VIBES</summary>
  <div class="project-content">
    <p class="project-text">We developed a multiscale agent-based model that combines within-host
    viral dynamics and between-hosts transmission dynamics. The viral dynamics model is fed with longitudinal
    viral load data of patients infected by the target pathogen, and it drives the infectiousness and disease
    progression in the transmission model.</p>
  </div>
</details>

<details class="project-dropdown" open>
  <summary>Forecasting of Respiratory Viral Diseases</summary>
  <div class="project-content">
    <p class="project-text">Add description here</p>
  </div>
</details>

<details class="project-dropdown" open>
  <summary>RSV Transmission Dynamics</summary>
  <div class="project-content">
    <p class="project-text">We develop compartmental model to simulate the spread of Respiratory Syncytial Virus
    (RSV) within populations. </p>
  </div>
</details>

<h2 class="research-area">Mosquito-Borne Diseases</h2>

<details class="project-dropdown">
  <summary>Forecasting relative abundance of mosquitoes in urban areas</summary>
  <div class="project-content">
    <p class="project-text">We developed an analytical tool to forecast the relative abundance
    of mosquito species in urban areas.The tool is a mechanistic and Bayesian framework, which estimates
    reproduction and generation parameters of a mosquito species based on weekly specimen collection data.
    We trained and validated our framework for Aedes aegypti collections in four urban locations of the USA 
    with diverse climate landscapes.</p>
  </div>
</details>