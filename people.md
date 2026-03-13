---
layout: default
title: People
permalink: /people/
---

<style>
  /* Style for the PI at the top */
  .pi-profile {
    display: flex;
    align-items: center;
    margin-bottom: 50px;
    margin-top: 30px;
    text-decoration: none; /* Removes default link underline */
    color: inherit; /* Keeps text from turning standard link-blue */
    transition: transform 0.3s ease; /* Smooth hover animation */
  }
  
  .pi-profile:hover {
    transform: translateY(-5px); /* Lifts the profile slightly when hovered */
  }

  .pi-profile img {
    border-radius: 50%;
    width: 200px;
    height: 200px;
    object-fit: cover; 
    margin-right: 30px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1); /* Adds a subtle drop shadow to the photo */
  }

  .pi-profile h2 {
    margin-top: 0; 
    border-bottom: none;
    transition: color 0.2s ease;
  }

  .pi-profile:hover h2 {
    color: #508c96; /* Turns the name teal on hover */
  }
  
  /* Style for the grid of team members */
  .team-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 40px;
    justify-content: flex-start;
  }
  
  .team-member {
    text-align: center;
    width: 180px;
    text-decoration: none;
    color: inherit;
    transition: transform 0.3s ease;
  }

  .team-member:hover {
    transform: translateY(-5px);
  }

  .team-member img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
    object-fit: cover;
    margin-bottom: 15px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  }
  
  .team-member h4 {
    margin: 0 0 5px 0;
    color: #2b2b2b;
    transition: color 0.2s ease;
  }

  .team-member:hover h4 {
    color: #508c96;
  }

  .team-member p {
    margin: 0;
    font-size: 0.9em;
    color: #555;
  }
</style>

<div class="subpage-banner">
  <div class="banner-left">
    <h1>People</h1>
  </div>
  <div class="banner-right"></div>
</div>

<a href="{{ '/people/marco-ajelli/' | relative_url }}" class="pi-profile" markdown="0">
  <img src="/images/people/marco-ajelli.jpg" alt="Marco Ajelli">
  <div>
    <h2>Marco Ajelli</h2>
    <p><strong>Professor</strong></p>
  </div>
</a>

<div class="team-grid">

  <a href="{{ '/people/paulo-ventura/' | relative_url }}" class="team-member" markdown="0">
    <img src="/images/people/paulo-ventura.jpg" alt="Paulo Ventura">
    <h4>Paulo Ventura</h4>
    <p>Postdoctoral Researcher</p>
  </a>
  
  <a href="{{ '/people/allisandra-kummer/' | relative_url }}" class="team-member" markdown="0">
    <img src="/images/people/allisandra-kummer.jpg" alt="Allisandra G. Kummer">
    <h4>Allisandra G. Kummer</h4>
    <p>Postdoctoral Researcher</p>
  </a>
  
  <a href="{{ '/people/shreeya-mhade/' | relative_url }}" class="team-member" markdown="0">
    <img src="/images/people/shreeya-mhade.jpg" alt="Shreeya Mhade">
    <h4>Shreeya Mhade</h4>
    <p>PhD Candidate</p>
  </a>

  <a href="{{ '/people/utkarsh-bhosekar/' | relative_url }}" class="team-member" markdown="0">
    <img src="/images/people/utkarsh-bhosekar.jpg" alt="Utkarsh Bhosekar">
    <h4>Utkarsh Bhosekar</h4>
    <p>Data Analyst</p>
  </a>

  <a href="{{ '/people/jessica-guerrini/' | relative_url }}" class="team-member" markdown="0">
    <img src="/images/people/jessica-guerrini.jpg" alt="Jessica Guerrini">
    <h4>Jessica Guerrini</h4>
    <p>Graduate Research Assistant</p>
  </a>

  <a href="{{ '/people/katie-pletz/' | relative_url }}" class="team-member" markdown="0">
    <img src="/images/people/katie-pletz.jpg" alt="Katie Pletz">
    <h4>Katie Pletz</h4>
    <p>Graduate Research Assistant</p>
  </a>

  <a href="{{ '/people/snigdha-agrawal/' | relative_url }}" class="team-member" markdown="0">
    <img src="/images/people/snigdha-agrawal.jpg" alt="Snigdha Agrawal">
    <h4>Snigdha Agrawal</h4>
    <p>Graduate Research Assistant</p>
  </a>

</div>

<div style="margin-top: 70px;">
  <h2 style="border-bottom: 2px solid #508c96; padding-bottom: 10px; margin-bottom: 20px;">Lab Alumni</h2>
  
  <ul style="list-style-type: none; padding-left: 0; font-size: 16px; line-height: 1.8;">
    <li>Luling Zou</li>
    <li>Megan Hill</li>
    <li>Anna Koebcke</li>
    <li>Claire Slotegraaf</li>
    <li>Jagadeesh Chitturi</li>
    <li>Andre Wilke</li>
    <li>Juanjuan Zhang (Visiting Scholar)</li>
    <li>Ethan SeRine</li>
    <li>Adquate Mhlanga</li>
    <li>Victorya Valentine</li>
    <li>Shelby Stone</li>
    <li>Samantha O'Dell</li>
  </ul>
</div>