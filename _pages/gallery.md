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
    /* DESKTOP: 3 items per row */
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

  /* TABLET & MOBILE: 2 items per row (Looks much better on iPhone) */
  @media (max-width: 768px) {
    .image-grid { gap: 10px; } /* Smaller gap on phone */
    
    .grid-item {
      /* (100% - 10px gap) / 2 items */
      flex: 0 0 calc((100% - 10px) / 2);
      padding: 5px; /* Smaller padding on phone */
    }
  }

  .grid-item:hover {
    transform: translateY(-3px);
  }

  /* --- THE SQUARE FIX --- */
  .grid-item img {
    width: 100%;
    
    /* MODERN MAGIC: This forces a perfect square shape always */
    aspect-ratio: 1 / 1; 
    object-fit: cover; /* Crops the image to fit the square */
    
    border-radius: 4px;
    margin-bottom: 5px;
    display: block;
  }

  .grid-caption {
    font-size: 0.9em;
    color: #555;
    font-weight: 600;
  }
  
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
  <div class="grid-item" style="max-width: 300px; flex: 0 0 300px;">
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
    <img src="/images/group_presentation.jpg" alt="Research Presentation">
    <div class="grid-caption">Research Group Presentation</div>
  </div>

  <div class="grid-item">
    <img src="/images/visiting_scholar.jpeg" alt="Visiting Scholar at UWaterloo">
    <div class="grid-caption">Visiting Scholar at University of Waterloo</div>
  </div>
</div>

## Life & Travels
<div class="image-grid">
  <div class="grid-item">
    <img src="/images/japan_square.jpg" alt="Travelling in Tokyo">
    <div class="grid-caption">Travelling in Tokyo</div>
  </div>
  
  <div class="grid-item">
    <img src="/images/mm2024_sqaure.jpg" alt="Magical Mirai">
    <div class="grid-caption">My Favorite Charater in Magical Mirai 2024</div>
  </div>
</div>
