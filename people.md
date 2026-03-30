---
layout: default
title: People
permalink: /people/
---

<style>
  /* Main Grid Container */
  .people-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* Forces 3 profiles per row on desktop */
    gap: 50px 30px; 
    margin-top: 40px;
  }
  
  /* Tablet View: Drops to 2 per row */
  @media screen and (max-width: 900px) {
    .people-grid {
      grid-template-columns: repeat(2, 1fr);
    }
    .alumni-list {
      grid-template-columns: repeat(2, 1fr); /* Keeps alumni list from squishing */
    }
  }

  /* Mobile Phone View: Drops to 1 per row */
  @media screen and (max-width: 600px) {
    .people-grid {
      grid-template-columns: 1fr;
    }
    
    .alumni-list {
      grid-template-columns: 1fr;
    }
  }

  /* Individual Profile */
  .profile-card {
    text-align: center;
    width: 100%; 
  }

  .profile-card a {
    display: inline-block;
    transition: transform 0.3s ease;
    width: 100%;
    text-decoration: none;
  }

  .profile-card a:hover {
    transform: translateY(-5px);
  }

  .profile-card img {
    border-radius: 4px;
    width: 100%;
    aspect-ratio: 5 / 4; 
    object-fit: cover;
    margin-bottom: 15px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    display: block;
  }
  
  /* One Font Size for everyone */
  .profile-card h4 {
    margin: 0 0 4px 0; 
    color: #2b2b2b; 
    font-size: 1.3em; 
    font-weight: 600; 
  }

  .profile-card p {
    margin: 0;
    font-size: 0.95em; 
    color: #666666; 
    line-height: 1.4;
    font-weight: 400;
  }

  /* Alumni Section */
  .alumni-section {
    margin-top: 70px;
  }
  
  .alumni-section h2 {
    border-bottom: 2px solid #508c96;
    padding-bottom: 10px;
    margin-bottom: 20px;
  }

  .alumni-list {
    list-style-type: none;
    padding-left: 0;
    font-size: 16px;
    line-height: 1.8;
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* Makes alumni 3-cols on desktop */
  }
</style>

<div class="subpage-banner">
  <div class="banner-left">
    <h1>People</h1>
  </div>
  <div class="banner-right"></div>
</div>

<div class="people-grid">

  <div class="profile-card">
    <a href="{{ '/people/marco-ajelli/' | relative_url }}">
      <img src="/images/people/marco-ajelli.png" alt="Marco Ajelli">
    </a>
    <h4>Marco Ajelli</h4>
    <p>Professor</p>
  </div>

  <div class="profile-card">
    <a href="{{ '/people/paulo-ventura/' | relative_url }}">
      <img src="/images/people/paulo-ventura.png" alt="Paulo Ventura">
    </a>
    <h4>Paulo Ventura</h4>
    <p>Postdoctoral Researcher</p>
  </div>
  
  <div class="profile-card">
    <a href="{{ '/people/allisandra-kummer/' | relative_url }}">
      <img src="/images/people/allisandra-kummer.png" alt="Allisandra G. Kummer">
    </a>
    <h4>Allisandra G. Kummer</h4>
    <p>Postdoctoral Researcher</p>
  </div>
  
  <div class="profile-card">
    <a href="{{ '/people/shreeya-mhade/' | relative_url }}">
      <img src="/images/people/shreeya-mhade.png" alt="Shreeya Mhade">
    </a>
    <h4>Shreeya Mhade</h4>
    <p>PhD Candidate</p>
  </div>

  <div class="profile-card">
    <a href="{{ '/people/utkarsh-bhosekar/' | relative_url }}">
      <img src="/images/people/utkarsh-bhosekar.png" alt="Utkarsh Bhosekar">
    </a>
    <h4>Utkarsh Bhosekar</h4>
    <p>Data Analyst</p>
  </div>

  <div class="profile-card">
    <a href="{{ '/people/jessica-guerrini/' | relative_url }}">
      <img src="/images/people/jessica-guerrini.png" alt="Jessica Guerrini">
    </a>
    <h4>Jessica Guerrini</h4>
    <p>Graduate Research Assistant</p>
  </div>

  <div class="profile-card">
    <a href="{{ '/people/katie-pletz/' | relative_url }}">
      <img src="/images/people/katie-pletz.png" alt="Katie Pletz">
    </a>
    <h4>Katie Pletz</h4>
    <p>Graduate Research Assistant</p>
  </div>

  <div class="profile-card">
    <a href="{{ '/people/snigdha-agrawal/' | relative_url }}">
      <img src="/images/people/snigdha-agrawal.png" alt="Snigdha Agrawal">
    </a>
    <h4>Snigdha Agrawal</h4>
    <p>Graduate Research Assistant</p>
  </div>

</div>

<div class="alumni-section">
  <h2>Lab Alumni</h2>
  <ul class="alumni-list">
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