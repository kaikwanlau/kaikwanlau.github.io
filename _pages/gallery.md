---
layout: archive
title: "Photo Gallery"
permalink: /gallery/
author_profile: true
---

<style>
  /* --- GRID LAYOUT --- */
  .image-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-bottom: 40px;
  }
  
  .grid-item {
    /* CALCULATION: (100% width - 40px total gap) / 3 items 
       This forces exactly 3 items per row.
    */
    flex: 0 0 calc((100% - 40px) / 3);
    
    background: #fff;
    padding: 10px;
    border: 1px solid #eee;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    text-align: center;
    transition: transform 0.2s;
    box-sizing: border-box;
  }

  /* Tablet: 2 items per row */
  @media (max-width: 768px) {
    .grid-item { flex: 0 0 calc((100% - 20px) / 2); }
  }
  
  /* Phone: 1 item per row */
  @media (max-width: 480px) {
    .grid-item { flex: 0 0 100%; }
  }

  .grid-item:hover {
    transform: translateY(-3px);
  }

  /* --- UNIFORM IMAGE SIZE --- */
  .grid-item img {
    width: 100%;
    height: 250px;      /* Fixed height for perfect alignment */
    object-fit: cover;  /* Crops excess edges so image doesn't stretch */
    border-radius: 4px;
    margin-bottom: 10px;
    display: block;
  }

  .grid-caption {
    font-size: 0.9em;
    color: #555;
    font-weight: 600;
  }
  
  /* Section Headers */
  h2 {
    margin-top: 30px;
    border-bottom: 1px solid #eee;
    padding-bottom: 10px;
    color: #333;
    clear: both;
  }
</style>

## Academic Profile
<div class="image-grid" style="justify-content: center;">
  <div class="grid-item" style="flex: 0 0 300px;">
    <img src="/images/professional2_square.jpg" alt="Academic Profile" style="object-fit: contain;">
    <div class="grid-caption">Academic Profile</div>
  </div>
</div>

## Research & International Experience
<div class="image-grid">
  <div class="grid-item">
    <img src="/images/lunch_with_justin.jpeg" alt="Lunch with Professor">
    <div class="grid-caption">Lunch with Prof. Justin Wan</div>
  </div>
  
  <div class="grid-item">
    <img src="/images/group_presentation.jpeg" alt="Research Presentation" style="object-position: top center;">
    <div class="grid-caption">Weekly Research Group Presentation</div>
  </div>

  <div class="grid-item">
    <img src="/images/visiting_scholar.jpg" alt="Visiting Scholar at UWaterloo">
    <div class="grid-caption">Visiting Scholar at University of Waterloo</div>
  </div>
</div>

## Life & Travels
<div class="image-grid">
  <div class="grid-item">
    <img src="/images/japan_square.jpg" alt="Japan Exchange">
    <div class="grid-caption">Travelling in Tokyo</div>
  </div>
  
  <div class="grid-item">
    <img src="/images/mm2024_sqaure.jpg" alt="Magical Mirai">
    <div class="grid-caption">My favorite character in Magical Mirai 2024 (Osaka)</div>
  </div>
</div>
