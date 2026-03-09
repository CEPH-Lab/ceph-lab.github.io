---
layout: default
title: Situational Awareness
permalink: /research/situational-awareness/
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
    width: 100%; 
    max-width: 600px;
    margin: 10px 0 20px 30px; /* Pushes text away from the left and bottom edges */
    border-radius: 8px;
    border: 1px solid #e5e5e5;
    box-shadow: 0 4px 15px rgba(0,0,0,0.05);
  }

  /* Full figure */
  .figure-full { 
  display: block; /* Forces it to take up its own full line */
  width: 100%; 
  max-width: 100%; 
  margin: 40px 0;
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
  <h1 class="project-title">Situational Awareness</h1>
  <span class="research-area-tag">Monitoring and Forecasting: The "Now and Next"</span>
</div>

<div class="project-body">

<img src="/images/research/sit-awareness/Fig01.png" alt="VIBES Framework" class="figure-right">

<h3 style="color: #508c96">Why Situational Awareness?</h3>
    <p>In the early stages of an outbreak or during seasonal surges, surveillance data is often delayed, incomplete,
    or biased. Despite these uncertainties, public health officials must still make time-sensitive choices. The role of
    situational awareness is to bridge this gap, providing the scientific evidence needed to navigate complex
    epidemiological landscapes. By integrating real-time surveillance with advanced modeling tools, we provide a clearer
    picture of an epidemic's current state (nowcasting) and its immediate trajectory (forecasting). This work is crucial
    in narrowing the distance between data collection and action, ensuring that evidence-based insights form the basis
    for public health decisions.</p>

<h3 style="color: #508c96">Research Topics</h3>
   <ul>
    <li><strong>Human Pathogens.</strong>The CEPH Lab develops models to monitor the spread of respiratory pathogens,
    such as influenza, RSV, and COVID-19, providing short-term (1- to 4-week-ahead) forecasts of epidemic burden
    (e.g., number of hospitalizations) to support public health and clinical preparedness and response planning.</li>
    <li><strong>Mosquito Population Dynamics.</strong> Situational awareness is not limited to human cases. 
    For vector-borne diseases (e.g., West Nile, dengue, Zika), public health actions often start with the vector. 
    We are developing analytical tools that forecast the abundance of Aedes aegypti and other vector species 1 to 4
    weeks ahead to inform the deployment of mosquito control strategies.</li>
   </ul>

<h3 style="color: #508c96">Approach</h3>
    <p>We use a set of approaches ranging from mechanistic modeling rooted in epidemiological and biological principles
    to statistical/machine learning modeling, and semi-mechanistic hybrid approaches based on data type and quality,
    and the specific public health needs.</p>

<h3 style="color: #508c96">Projects and Impact</h3>
    <ul>
    <li><strong>CDC Forecasting Hubs:</strong> We maintain a long-standing contribution to national forecasting
    efforts for seasonal and pandemic threats through our participation to CDC-led forecasting initiatives such as
    <a href="https://www.cdc.gov/flu-forecasting/" style="color: #508c96">FluSight</a>, the
    <a href="https://covid19forecasthub.org/" style="color: #508c96">COVID-19 forecast hub</a>, and the 
    <a href="https://rsvforecasthub.org/" style="color: #508c96">RSV forecast hub</a>.</li>
    <li><strong>Mosquito Forecasting Tools:</strong> Our forecasting tools have been tested across multiple US
    jurisdictions to enhance situational awareness of partners such as the Miami-Dade County Mosquito Control, 
    Maricopa, Los Angeles, and New Orleans</li>
    </ul>

<h3 style="color: #508c96">Funding</h3>
    <ul>
    <li>Our infectious disease forecasting efforts are supported by 
    <a href="https://www.epistorm.org/" style="color: #508c96">Epistorm</a>, a center-level grant funded by the
    CDC.</li>
    <li>Our mosquito population forecasting efforts are supported by the NSF</li>
    </ul>

</div>