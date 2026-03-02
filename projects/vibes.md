---
layout: default
title: VIBES
permalink: /projects/vibes/
---

<style>
  .project-header {
    margin-top: 40px;
    margin-bottom: 30px;
    border-bottom: 2px solid #508c96;
    padding-bottom: 10px;
  }
  
  .project-title {
    color: #2b2b2b;
    font-size: 32px;
    margin: 0 0 10px 0;
  }
  
  .research-area-tag {
    display: inline-block;
    background-color: #f0f6f7;
    color: #508c96;
    padding: 5px 12px;
    border-radius: 4px;
    font-size: 14px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1px;
  }

  .back-link {
    display: inline-block;
    margin-top: 20px;
    color: #508c96;
    text-decoration: none;
    font-weight: 600;
    font-size: 15px;
  }
  
  .back-link:hover {
    text-decoration: underline;
  }

  .project-body {
    font-size: 16px;
    line-height: 1.8;
    color: #444;
    margin-top: 30px;
  }
</style>

<a href="{{ '/projects/' | relative_url }}" class="back-link">← Back to All Projects</a>

<div class="project-header">
  <span class="research-area-tag">Multi-scale Modeling</span>
  <h1 class="project-title">VIBES: A Multi-Scale Modeling Approach Integrating Within-Host and Between-Hosts 
    Dynamics in Epidemics</h1>
</div>

<div class="project-body">
  <p>Infectious disease spread is a complex, multi-scale process driven by the continuous interaction 
    between biological (within-host) and social (between-host) factors. To truly understand epidemic dynamics, 
    both of these drivers must be evaluated together rather than in isolation. To address this, we developed
    <strong>VIBES</strong>, a multi-scale Individual-Based Modeling framework that explicitly integrates 
    individual-level viral dynamics with population-level transmission over a data-driven network of social contacts.</p>

  <h3>How the Framework Operates</h3>
  <p>VIBES bridges the gap between viral dynamics and human behavior by simulating disease transmission at two distinct levels:</p>
  <ul>
    <li><strong>The Biological Layer:</strong> The model simulates viral replication and elimination within each individual host. This provides an individualized viral load trajectory that dictates a person's exact infectiousness profile over time.</li>
    <li><strong>The Social Layer:</strong> These individual profiles are projected onto a highly-resolved synthetic population of 500,000 agents (statistically calibrated to represent Indiana, USA). Transmission events occur across four specific social settings: households, schools, workplaces, and the broader community.</li>
  </ul>

  <h3>Key Insights & Capabilities</h3>
  <p>Using SARS-CoV-2 as a primary case study, VIBES allows us to mechanistically quantify how interventions and pathogen mutations shape epidemic dynamics. By tracking individual infections across the network, we can directly calculate generation times, serial intervals, and pre-symptomatic transmission rates.</p>
  
  <ul>
    <li><strong>Disentangling Drivers:</strong> By establishing a purely biological baseline, we estimated a generation time of 6.3 days with 43.1% pre-symptomatic transmission. However, when introducing real-world social contacts, competition among infectious individuals shortened the generation time to 5.4 days and increased pre-symptomatic transmission to 52.8% (at R=3.0).</li>
    <li><strong>Transmissibility Effects:</strong> As pathogen transmissibility increases (R=1.3 up to 6), the generation time and serial interval can shorten by up to 21% and 13%, respectively.</li>
    <li><strong>Assessing Interventions:</strong> VIBES demonstrates how behavioral shifts alter transmission dynamics. For instance, implementing social interventions like isolating symptomatic individuals can increase the proportion of pre-symptomatic transmission by approximately 30%.</li>
    <li><strong>Estimating Unobservable Metrics:</strong> The framework successfully estimates notoriously difficult epidemiological metrics, such as the generation time for completely asymptomatic individuals (estimated at 5.6 days).</li>
  </ul>

  <h3>Featured Publication</h3>
  <p>For a comprehensive review of the VIBES framework, methodology, and the full SARS-CoV-2 analysis, please view our preprint:</p>
  
  <div class="citation-box">
    <p style="margin: 0;">Ventura PC, Jeong YD, Litvinova M, Kummer AG, Iwami S, Yu H, Merler S, Vespignani A, Ejima K, <strong>Ajelli M</strong>. (2025). <em>VIBES: A Multi-Scale Modeling Approach Integrating Within-Host and Between-Hosts Dynamics in Epidemics</em>. arXiv:2508.13354.</p>
    <a href="https://doi.org/10.48550/arXiv.2508.13354" target="_blank" style="display: inline-block; margin-top: 10px; color: #508c96; font-weight: 600; text-decoration: none;">[Read the Full Paper]</a>
  </div>
</div>