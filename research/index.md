---
layout: default
title: Research
permalink: /research/
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
    font-size: 20px;
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
  <p>The CEPH lab focuses on five main research lines in infectious disease epidemiology and public health. 
    Select a card below to learn more about what we do.</p>
</div>

<!--
<h2 class="section-header">Forecasting of Respiratory Viral Diseases</h2>

<div class="project-card">
  <h3 class="project-title">Rtrend</h3>
  <p class="project-summary">Rtrend is a renewal equation model that combines a gamma-distributed generation time,
    past incidence data, and forecasted trajectories of the reproduction number to forecast the incidence of
    infections for respiratory pathogens. We use this model to produce forecasts for influenza, RSV, and COVID-19.</p>
  <a href="{{ '/research/Rtrend/' | relative_url }}" class="read-more-btn">Learn More</a>
</div>

<h2 class="section-header">Intervention Assessment</h2>
<div class="project-card">
  <h3 class="project-title">Individual-Based Epidemic Simulator</h3>
  <p class="project-summary">Individual-Based Epidemic Simulator (IBES) is an agent-based modeling tool for
    simulating the transmission dynamics of respiratory pathogens and conducting non-pharmaceutical intervention
    assessments that mitigate infectious disease spread for large-scale synthetic populations.</p>
  <a href="{{ '/research/ibes/' | relative_url }}" class="read-more-btn">Learn More</a>
</div>

<div class="project-card">
  <h3 class="project-title">Scenario Modeling Hub</h3>
  <p class="project-summary">Our work with the Scenario Modeling Hub consists of performing model-based scenario
    analyses that compare outbreak trajectories for different interventions, pathogens, and populations that impact
    disease spread. We currently submit projections for the RSV, Flu, and Pandemic cryptic phase modeling hubs.</p>
  <a href="{{ '/research/smh/' | relative_url }}" class="read-more-btn">Learn More</a>
</div>

<div class="project-card">
  <h3 class="project-title">ASTRA</h3>
  <p class="project-summary">Annual Scenarios of Transmission (ASTRA) is a deterministic, age-stratified compartmental
    model that was developed to conduct scenario analyses for respiratory infectious diseases.</p>
  <a href="{{ '/research/astra/' | relative_url }}" class="read-more-btn">Learn More</a>
</div>
-->

<h2 class="section-header">Main Research Lines</h2>

<div class="project-card">
  <h3 class="project-title">Public Health Planning</h3>
  <p class="project-summary">Mathematical and computational models have increasingly been used to inform
    epidemic preparedness and response. Our objective is to support public health decision-making through the 
    scenario analysis and model-based evaluations of pharmaceutical and non-pharmaceutical interventions.
    We provide actionable insights to our national and international public health partners and conduct
    fundamental research in this area.</p>
  <a href="{{ '/projects/vibes/' | relative_url }}" class="read-more-btn">Learn More</a>
</div>

<div class="project-card">
  <h3 class="project-title">Situational Awareness</h3>
  <p class="project-summary">Situational awareness is key for public health policy-making as it allows anticipating 
    surges in disease burden (e.g., hospitalizations) and trigger early warnings. Our objective is to 
    enhance situational awareness through nowcasting and forecasting of epidemic trajectories using a variety of 
    approaches from mechanistic, to semi-mechanistic, and stastical/machine learning approaches. We also aim at
    improving situational awareness of mosquito control authorities by forecasting mosquito population dynamics.</p>
  <a href="{{ '/projects/vibes/' | relative_url }}" class="read-more-btn">Learn More</a>
</div>

<div class="project-card">
  <h3 class="project-title">Infectious Disease Dynamics</h3>
  <p class="project-summary">The transmission of infectious pathogens is a complex process driven by the interplay
    of biological, behavioral, and socio-economic factors. Our objective is to characterize the fundamental
    mechanisms of pathogen spread, ranging from the clinical progression of individual infections to the broad
    patterns observed at the population level. We also aim to understand how cross-scale (within-host,
    between-host) interactions and socio-economic drivers shape the heterogeneous landscape of infectious disease
    epidemiology.</p>
  <a href="{{ '/projects/vibes/' | relative_url }}" class="read-more-btn">Learn More</a>
</div>

<div class="project-card">
  <h3 class="project-title">Human Social Interactions</h3>
  <p class="project-summary">Social mixing patterns drive respiratory pathogen transmission leading to 
    heterogeneous exposure risks across different socio-demographic groups. Our objective is to 
    understand why, where, when, how often, and with whom individuals interact to better characterize transmission
    pathways.</p>
  <a href="{{ '/projects/vibes/' | relative_url }}" class="read-more-btn">Learn More</a>
</div>

<div class="project-card">
  <h3 class="project-title">Mosquito Ecology and Behavior</h3>
  <p class="project-summary">The relative abundance and behavior of mosquito vector species are main determinants of 
    human risks for mosquito-borne diseases. Our objective is to investigate the drivers of seasonal and diel
    trends in mosquito population dynamics and behavior across space and time to identify the underlying mechanisms. 
    Through a mechanistic understanding of these processes, we carry out model-based evaluations to inform
    mosquito-control and public health authorities.</p>
  <a href="{{ '/projects/epistorm-mix/' | relative_url }}" class="read-more-btn">Learn More</a>
</div>