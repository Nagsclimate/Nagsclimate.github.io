---
layout: splash
permalink: /
title: ""  # No title shown
header:
  overlay_image: /assets/city-pics/Bologna.jpeg
  overlay_filter: 0.6
  caption: "Photo credit: [**Nags**](https://unsplash.com)"
  actions: []
---

<style>
  .hero-overlay {
    position: absolute;
    top: 40%;
    left: 50%;
    transform: translate(-50%, -50%);
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    color: white;
    text-align: left;
    width: 90%;
    max-width: 1200px;
  }

  .hero-text {
    flex: 1 1 500px;
    padding-right: 2rem;
    font-size: 1.1rem;
    line-height: 1.6;
  }

  .hero-image {
    flex: 0 1 300px;
    text-align: center;
  }

  .hero-image img {
    max-width: 100%;
    border-radius: 10px;
    box-shadow: 0 0 12px rgba(0,0,0,0.3);
  }

  @media (max-width: 768px) {
    .hero-overlay {
      flex-direction: column;
      top: 50%;
      transform: translate(-50%, -50%);
    }
    .hero-text {
      padding-right: 0;
      margin-bottom: 1.5rem;
    }
  }
</style>

<div class="hero-overlay">
  <!-- Left Text -->
  <div class="hero-text">
    <h2>Welcome</h2>
    <p>
      Welcome to my website—a space where science meets cities, and climate meets community.<br><br>
      As urbanization accelerates, cities face rising challenges from extreme heat, flooding, and climate inequality. My work bridges science and society—using modeling, remote sensing, and data science to help shape resilient and just urban futures.
    </p>
    <p><strong id="datetime"></strong></p>
    <script>
      document.getElementById("datetime").innerText = new Date().toLocaleString();
    </script>
  </div>

  <!-- Right Image -->
  <div class="hero-image">
    <img src="/assets/images/nags.jpg" alt="Nagaraju Gaddam">
  </div>
</div>
