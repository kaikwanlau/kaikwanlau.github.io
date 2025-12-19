---
layout: archive
title: "Digital Art / イラスト"
permalink: /art/
author_profile: true
---

<div id="art-portfolio-container">

  <style>
    /* --- BUTTON AREA (Language) --- */
    .lang-switcher {
      text-align: center;
      margin-bottom: 30px;
    }
    .lang-btn {
      display: inline-block;
      border: 2px solid #e0e0e0;
      border-radius: 20px;
      padding: 6px 18px;
      cursor: pointer;
      font-weight: bold;
      color: #999;
      margin: 0 5px;
      transition: all 0.2s;
      background: white;
      user-select: none;
    }
    .lang-btn:hover { border-color: #0096fa; color: #0096fa; }
    .lang-btn.active-mode { background-color: #f0f8ff; border-color: #0096fa; color: #0096fa; }

    /* --- GRID LAYOUT (3 items per row) --- */
    .image-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-bottom: 40px;
    }
    
    .grid-item {
      /* Calculation: (100% width - 40px gap) / 3 items */
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

    .grid-item:hover { transform: translateY(-3px); }
    .grid-item img {
      width: 100%;
      height: auto;
      border-radius: 4px;
      margin-bottom: 10px;
      display: block;
    }
    .grid-caption { font-size: 0.9em; color: #555; font-weight: 600; }

    /* --- BEAUTIFUL SOCIAL BUTTONS --- */
    .social-section {
      border-top: 1px solid #eaeaea;
      padding-top: 40px;
      margin-top: 50px;
      text-align: center;
    }
    
    .social-buttons-wrapper {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin-top: 25px;
    }

    .social-btn {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 220px;
      padding: 12px 0;
      border-radius: 50px;
      text-decoration: none !important;
      font-weight: 700;
      font-size: 1em;
      transition: all 0.3s ease;
      background: #fff;
      box-shadow: 0 4px 6px rgba(0,0,0,0.05);
    }

    .social-btn i {
      font-size: 1.3em;
      margin-right: 10px;
    }

    /* Pixiv Style */
    .btn-pixiv { border: 2px solid #0096fa; color: #0096fa; }
    .btn-pixiv:hover {
      background-color: #0096fa;
      color: #fff;
      transform: translateY(-4px);
      box-shadow: 0 10px 20px rgba(0, 150, 250, 0.25);
    }

    /* Instagram Style */
    .btn-insta { border: 2px solid #E1306C; color: #E1306C; }
    .btn-insta:hover {
      background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
      border-color: transparent;
      color: #fff;
      transform: translateY(-4px);
      box-shadow: 0 10px 20px rgba(220, 39, 67, 0.25);
    }
  </style>

  <div class="lang-switcher">
    <span class="lang-btn active-mode" id="btn-en" onclick="window.switchArt('en')">English</span>
    <span class="lang-btn" id="btn-jp" onclick="window.switchArt('jp')">日本語</span>
  </div>

  <div id="content-en" style="display: block;">
    <p style="text-align: center;">
      Outside of mathematics, I am a digital artist and a fan of Hatsune Miku.
    </p>

    <h2 style="text-align: center; border-bottom: none; margin-top: 30px;">Illustrations & Fan Art</h2>

    <div class="image-grid">
      <div class="grid-item">
        <img src="/images/IMG_mm19.JPG" alt="Magical Mirai 2019">
        <div class="grid-caption">Magical Mirai 2019</div>
      </div>
      
      <div class="grid-item">
        <img src="/images/IMG_mm20.JPG" alt="Magical Mirai 2020">
        <div class="grid-caption">Magical Mirai 2020</div>
      </div>

      <div class="grid-item">
        <img src="/images/IMG_snowmiku2018.JPG" alt="Snow Miku 2018">
        <div class="grid-caption">Snow Miku 2018</div>
      </div>

      <div class="grid-item">
        <img src="/images/IMG_kaguya.JPG" alt="Kaguya-sama">
        <div class="grid-caption">Kaguya-sama: Love Is War</div>
      </div>

      <div class="grid-item">
        <img src="/images/IMG_takagi.JPG" alt="Takagi-san">
        <div class="grid-caption">Teasing Master Takagi-san</div>
      </div>
    </div>
  </div>

  <div id="content-jp" style="display: none;">
    <p style="text-align: center;">
      数学の研究以外では、デジタルアーティストとしても活動しており、初音ミクの大ファンです。
    </p>

    <h2 style="text-align: center; border-bottom: none; margin-top: 30px;">イラスト・ファンアート</h2>

    <div class="image-grid">
      <div class="grid-item">
        <img src="/images/IMG_mm19.JPG" alt="Magical Mirai 2019">
        <div class="grid-caption">初音ミク「マジカルミライ 2019」</div>
      </div>
      
      <div class="grid-item">
        <img src="/images/IMG_mm20.JPG" alt="Magical Mirai 2020">
        <div class="grid-caption">初音ミク「マジカルミライ 2020」</div>
      </div>

      <div class="grid-item">
        <img src="/images/IMG_snowmiku2018.JPG" alt="Snow Miku 2018">
        <div class="grid-caption">雪ミク 2018</div>
      </div>

      <div class="grid-item">
        <img src="/images/IMG_kaguya.JPG" alt="Kaguya-sama">
        <div class="grid-caption">かぐや様は告らせたい</div>
      </div>

      <div class="grid-item">
        <img src="/images/IMG_takagi.JPG" alt="Takagi-san">
        <div class="grid-caption">からかい上手の高木さん</div>
      </div>
    </div>
  </div>

  <div class="social-section">
    <p style="color: #666; font-size: 1.0em; margin-bottom: 5px;">
      <span id="social-text-en">Follow my latest works and sketches:</span>
      <span id="social-text-jp" style="display:none;">最新の作品やスケッチはこちら:</span>
    </p>

    <div class="social-buttons-wrapper">
      <a href="https://www.pixiv.net/users/104021355" target="_blank" class="social-btn btn-pixiv">
        <i class="fas fa-paint-brush"></i> Pixiv Portfolio
      </a>

      <a href="https://www.instagram.com/kaikwankundesu/" target="_blank" class="social-btn btn-insta">
        <i class="fab fa-instagram"></i> @kaikwankundesu
      </a>
    </div>
  </div>

  <script>
    window.switchArt = function(lang) {
      var btnEn = document.getElementById('btn-en');
      var btnJp = document.getElementById('btn-jp');
      var divEn = document.getElementById('content-en');
      var divJp = document.getElementById('content-jp');
      var socEn = document.getElementById('social-text-en');
      var socJp = document.getElementById('social-text-jp');

      if (lang === 'en') {
        divEn.style.display = 'block';
        divJp.style.display = 'none';
        socEn.style.display = 'inline';
        socJp.style.display = 'none';
        btnEn.classList.add('active-mode');
        btnJp.classList.remove('active-mode');
      } else {
        divEn.style.display = 'none';
        divJp.style.display = 'block';
        socEn.style.display = 'none';
        socJp.style.display = 'inline';
        btnJp.classList.add('active-mode');
        btnEn.classList.remove('active-mode');
      }
    };
  </script>

</div>
