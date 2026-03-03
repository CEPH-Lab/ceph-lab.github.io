---
layout: default
title: Home
permalink: /
---
<style>
  /* --- Hero Banner Styling --- */
  .hero {
    position: relative;
    height: 90vh; /* Takes up 90% of the screen height to leave room for the top navigation bar */
    width: 100vw;
    margin-left: calc(-50vw + 50%); /* Magic CSS trick to break out of the 1200px wrapper */
    margin-top: -30px; /* Pulls the image up flush against the header */
    margin-bottom: 60px;
    
    /* Uses your specific banner.png file */
    background-image: linear-gradient(rgba(15, 32, 39, 0.6), rgba(32, 58, 67, 0.7)), url('/images/banner.png');
    background-size: cover;
    background-position: center;
    background-attachment: fixed; /* Creates the parallax scrolling effect */
    
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
  display: flex; /* Helps center the new chevron */
  justify-content: center;
  align-items: center;
  height: 50px; /* Gives a clickable area */
  width: 50px;
  margin-top: -20px; /* Adjust spacing since the text size changed */
  text-decoration: none;
  animation: bounce 2s infinite;
  opacity: 0.6; /* Fades the arrow slightly for a subtle look */
  transition: opacity 0.3s ease;
  }

  .scroll-down:hover {
  opacity: 1; /* Highlights the arrow when the user interacts with it */
  }

  /* Drawing the subtle chevron using pseudo-elements */
  .scroll-down::after {
  content: '';
  display: block;
  width: 15px; /* Smaller, more subtle width */
  height: 15px; /* Smaller, more subtle height */
  border-bottom: 2px solid #42e8e0; /* Thin teal line matches previous accent color */
  border-right: 2px solid #42e8e0; /* Thin teal line matches previous accent color */
  transform: rotate(45deg); /* Rotates the square to make a 'V' shape */
  }

    /* Updated bounce animation */
    @keyframes bounce {
      0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
      /* Reduced bounce height from -20px and -10px down to -10px and -5px */
      40% { transform: translateY(-10px); }
      60% { transform: translateY(-5px); }
    }

  /* --- Existing Text Styling --- */
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

  /* --- Mobile Responsiveness for the Hero Banner --- */
  @media screen and (max-width: 768px) {
    .hero h1 {
      font-size: 2rem; /* Shrinks the massive title for phones */
      margin-top: 20px;
    }
    
    .hero p {
      font-size: 1.1rem; /* Shrinks the subtext */
      margin-bottom: 20px;
    }
    
    .scroll-down {
      height: 40px; /* Makes the arrow slightly smaller */
      width: 40px;
    }
  }

</style>

<div class="hero">
  <h1>Where Ideas Inspire Action</h1>
  <p>We are committed to advancing the understanding of epidemic spread and informing public health decision-making</p>
  <a href="#mission" class="scroll-down" aria-label="Scroll to Mission"></a>
</div>

<div id="mission"></div>

<h2 class="section-header">Mission</h2>
<div class="mission-text">
  <p>Our mission at the Laboratory for Computational Epidemiology and Public Health (CEPH Lab) is
    to advance the understanding of infectious disease epidemiology and provide actionable insights to inform 
    public health policy. 

<!--
    is to advance the understanding of infectious disease dynamics through applied infectious
    disease epidemiology and mathematical modeling. By studying infectious disease outbreaks and
    developing modeling tools, we provide actionable insights that inform public health decision-making and strengthen
    preparedness and response planning.
-->
</p>
</div>

<h2 class="section-header">What we do</h2>
<div class="mission-text">
<ul class="what-we-do-list">
  <li>Develop mathematical and computational modeling tools that simulate infectious disease transmission
    to investigate epidemic spread</li>
  <li>Apply statistical modeling to identify the socio-economic, behavioral, and environmental determinants of 
    the epidemiology of infectious diseases and the ecology of their vectors</li>
  <li>Conduct model-based evaluations of the effectiveness of public health interventions to inform public health
    decision-making</li>
  <li>Forecast and nowcast infectious disease dynamics and vector populations to enhance public health 
    situational awareness</li>
</ul>
</div>

<!--
<h2 class="section-header">Research Areas</h2>

<details class="research-card">
  <summary>Public Health Planning</summary>
  <div class="research-content">
    <p class="research-text">We evaluate the potential impact of public health interventions against respiratory
    infectious diseases through the development of mathematical models and participating in the Scenario 
    Modeling Hub(SMH) for Respiratory Syncytial Virus (RSV), Influenza (Flu) and Pandemic cryptic phase.
    By simulating various scenarios, we assess the epidemiological impacts of pharmaceutical interventions,
    vaccination strategies, and non-pharmaceutical measures.</p>
  </div>
</details>

<details class="research-card">
  <summary>Situational Awareness</summary>
  <div class="research-content">
    <p class="research-text">Situational awareness is key for public health policy-making as it allows to anticipate 
    surges in disease burden (e.g., hospitalizations) and trigger early warnings. Our objective is to 
    enhance situational awareness through nowcasting and forecasting of epidemic trajectories using a variety of 
    approaches from mechanistic, to semi-mechanistic, and stastical/machine learning approaches. We also aim at
    improving situational awareness of mosquito control authorities by forecasting mosquito population dynamics.</p>
  </div>
</details>

<details class="research-card">
  <summary>Infectious Disease Dynamics</summary>
  <div class="research-content">
    <p class="research-text">As disease spread is an inherently multi-scale process, we build a data driven,
    multi-scale framework to simulate respiratory pathogen transmission at within-host and between-hosts scales.
    Our multi-scale framework integrates granular mobility, demographic, and behavioral data to capture
    the complex dynamics of epidemic spread at the individual and population level.</p>
  </div>
</details>

<details class="research-card">
  <summary>Human Social Interactions</summary>
  <div class="research-content">
    <p class="research-text">Social mixing patterns drive respiratory pathogen transmission leading to 
    heterogeneous exposure risks across different socio-demographic groups. Our objective is to 
    understand why, where, when, how often, and with whom individuals interact. </p>
  </div>
</details>

<details class="research-card">
  <summary>Mosquito Ecology and Behavior</summary>
  <div class="research-content">
    <p class="research-text"> The relative abundance and behavior of mosquito vector species are main determinants of 
    human risks for mosquito-borne diseases. Our objective is to investigate the drivers of seasonal and diel
    trends in mosquito population dynamics and behavior across space and time to identify the underlying mechanisms. 
    Through a mechanistic understanding of these processes, we carry out model-based evaluations to inform
    mosquito-control and public health authorities.</p>
  </div>
</details>
-->
