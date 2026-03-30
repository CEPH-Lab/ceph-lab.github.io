---
layout: default
title: Infectious Disease Dynamics
permalink: /research/infectious-disease-dynamics/
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

  /* Text Wrap Image Styling */
  .figure-right {
    float: right;
    width: 50%; /* Takes up half the page */
    max-width: 450px;
    margin: 10px 0 20px 30px; /* Pushes text away from the left and bottom edges */
    border-radius: 8px;
    border: 1px solid #e5e5e5;
    box-shadow: 0 4px 15px rgba(0,0,0,0.05);
  }

  /* Mobile Fix: Stops wrapping on small screens so text doesn't get squished */
  @media (max-width: 768px) {
    .figure-right {
      float: none;
      width: 100%;
      max-width: 100%;
      margin: 20px 0;
      display: block;
    }
  }
</style>

<a href="{{ '/research/' | relative_url }}" class="back-link">← Back to Research</a>

<div class="project-header">
  <h1 class="project-title">Infectious Disease Dynamics</h1>
  <span class="research-area-tag">The "How"</span>
</div>

<div class="project-body">

  <img src="/images/research/inf-dis-dynamics/Fig01.png" alt="Seasonality" class="figure-right">

<h3 style="color: #508c96">Why Infectious Disease Dynamics?</h3>
  <p>Understanding infectious disease dynamics requires disentangling the biological and social processes that drive
    spread. By investigating how individual-level factors (e.g., viral replication and clinical progression, social
    contacts, behavioral choices) shape population-level patterns, our goal is to understand the epidemic potential
    to cause major harm and to identify the mechanisms that lead to differences in disease burdens across different
    demographic and socio-economic groups. </p>
    
  <h3 style="color: #508c96">Research Topics</h3>
  <ul>
    <li><strong>Cross-Scale Interactions. </strong>
    Our research explores the link between individual-level viral replication and clinical progression (within-host)
    and population-level epidemic trajectories (between-host). </li>
    <li><strong>Disease Burden Heterogeneities. </strong>
    We analyze how factors such as age, gender, race/ethnicity, income level, and occupation shape the heterogeneous
    landscape of exposure and immunity, which ultimately leads to a heterogeneous burden of infectious diseases.</li>
    <li><strong>Estimation of Key Epidemiological Parameters. </strong>
    We use statistical approaches to estimate fundamental parameters that define an epidemic outbreak potential and
    severity, such as the reproduction number, generation time, and infection hospitalization risk.</li>
  </ul>

  <h3 style="color: #508c96">Approach</h3>
  <p>We utilize a variety of analytical frameworks, including statistical modeling, mechanistic modeling of
    between-host transmission and within-host viral dynamics, and hybrid approaches to analyze and interpret
    epidemiological data. Our modeling work is grounded in empirical evidence from a variety of data streams,
    including individual-level clinical data, contact tracing records, and socio-economic datasets.</p>
    
  <h3 style="color: #508c96">Impact</h3>
  <ul>
    <li><strong>Refining Epidemiological Theory: </strong>We conduct fundamental research that bridges the gap
    between clinical data and population-wide observation, providing a quantitative backbone for a deeper
    understanding of epidemic spread and how to model it.</li>
    <li><strong>Characterizing Epidemic Outbreaks: </strong>Our work provides real-time evidence to understand how
    an outbreak may unfold and which population groups will be more affected.</li>
  </ul>
    
  <h3 style="color: #508c96">Funding</h3>
  <ul>
    <li>Our research on infectious disease dynamics is supported by the CDC and NSF.</li>
  </ul>

  <h3 style="color: #508c96">References</h3>
  <ul>
    <li>
      <div class="citation-box">
        <p style="margin: 0; padding-bottom: 5px;">Ventura PC, Jeong YD, Litvinova M, Kummer AG, Iwami S, Yu H, Merler S, Vespignani A, Ejima K,
        Ajelli M.</p>
        <p style="margin: 0;"><em><a href="https://doi.org/10.48550/arXiv.2508.13354" style="color: #508c96">
        VIBES: A Multi-Scale Modeling Approach Integrating Within-Host and Between-Hosts Dynamics in Epidemics.</a>
        </em> Proceedings of the National Academy of Sciences. 2026;123 (13):e2523055123</p>
      </div>
    </li>
    <li>
      <div class="citation-box">
        <p style="margin: 0; padding-bottom: 5px;">Kummer AG, Zhang J, Jiang C, Litvinova M, Ventura PC, Garcia MA, Vespignani A, Wu H, Yu H,
        Ajelli M.</p>
        <p style="margin: 0;"><em><a href="https://doi.org/10.1111/irv.13301" style="color: #508c96">
        Evaluating Seasonal Variations in Human Contact Patterns and Their Impact on the Transmission of Respiratory
        Infectious Diseases.</a></em> Influenza Resp Viruses. 2024;18(5):e13301.</p>
      </div>
    </li>
  </ul>
</div>