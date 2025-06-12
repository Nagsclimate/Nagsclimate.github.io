---
layout: splash
permalink: /
classes: wide
title: ""
header:
  overlay_image: assets/city-pics/Bologna.jpeg
  overlay_filter: 0.5
  caption: "Photo credit: [**Nagssh**](https://unsplash.com)"
  actions:
    - label: "Learn More"
      url: "https://nagsclimate.github.io/about/"
    - label: "Join us"
      url: "https://nagsclimate.github.io/join-us/"
---

<style>
.hero-overlay {
  position: absolute;
  top: 100px; /* adjust as needed */
  left: 50%;
  transform: translateX(-50%);
  width: 90%;
  max-width: 1100px;
  background: rgba(255, 255, 255, 0.85);
  padding: 2rem;
  border-radius: 12px;
  display: flex;
  align-items: center;
  box-shadow: 0 10px 30px rgba(0,0,0,0.2);
  z-index: 10;
}

.hero-overlay img {
  width: 220px;
  border-radius: 10px;
  margin-right: 2rem;
  box-shadow: 0 4px 12px rgba(0,0,0,0.2);
}

.hero-text {
  flex: 1;
  font-size: 1rem;
  color: #222;
  line-height: 1.6;
}

@media (max-width: 768px) {
  .hero-overlay {
    flex-direction: column;
    text-align: center;
    padding: 1.5rem;
  }

  .hero-overlay img {
    margin: 0 0 1.5rem 0;
    width: 160px;
  }
}
</style>

<div class="hero-overlay">
  <img src="/assets/logos/Nags.jpg" alt="Nagaraju Gaddam">
  <div class="hero-text">
    <h2>Welcome to Nags Climate</h2>
    <p>
      I’m passionate about exploring how cities and climate intersect. Urban environments are at the forefront of some of the world’s most pressing challenges—from heatwaves to flooding, and climate inequality.
    </p>
    <p>
      My research blends data science, atmospheric modeling, and remote sensing to uncover how cities function under climate stress, and how we can build more resilient, just urban futures.
    </p>
  </div>
</div>
