---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

<style>
  /* 1. Grid Container */
  .image-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-bottom: 40px;
  }
  
  /* 2. Individual Items */
  .grid-item {
    flex: 1 0 250px; /* Min width 250px */
    max-width: 400px;
    background: #fff;
    padding: 10px;
    border: 1px solid #eee;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    text-align: center;
    transition: transform 0.2s;
  }

  .grid-item:hover {
    transform: translateY(-3px); /* Subtle lift effect */
  }

  /* 3. The Images */
  .grid-item img {
    width: 100%;
    height: auto;
    border-radius: 4px;
    margin-bottom: 8px;
  }

  /* 4. Captions */
  .grid-caption {
    font-size: 0.9em;
    color: #555;
    font-weight: 600;
  }
</style>

## Academic & Professional
<div class="image-grid">

  <div class="grid-item">
    <img src="/images/professional2_square.jpg" alt="Professional Headshot">
    <div class="grid-caption">Academic Profile</div>
  </div>

  </div>

## Life & Travels
<div class="image-grid">

  <div class="grid-item">
    <img src="/images/japan_square.jpg" alt="Travel in Japan">
    <div class="grid-caption">Travelling in Tokyo, photo taken by Hei</div>
  </div>

  <div class="grid-item">
    <img src="/images/mm2024_sqaure.jpg" alt="Magical Mirai 2024">
    <div class="grid-caption">My favorite charater in Magical Mirai 2024</div>
  </div>

</div>
