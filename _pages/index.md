---
layout: splash
permalink: /
classes: wide
title: ""
header:
  overlay_image: assets/city-pics/Bologna.jpeg
  overlay_filter: 0.6
  caption: "Photo credit: [**Nagssh**](https://unsplash.com)"
---

<style>
.hero-container {
  position: absolute;
  top: 120px; /* adjust for vertical position */
  left: 50%;
  transform: translateX(-50%);
  width: 90%;
  max-width: 1100px;
  background: rgba(255, 255, 255, 0.85);
  padding: 2rem;
  border-radius: 12px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  box-shadow: 0 10px 30px rgba(0,0,0,0.2);
  z-index: 10;
}

.hero-image {
  width: 220px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.2);
  flex-shrink: 0;
}

.hero-text {
  flex: 1;
  margin-left: 2rem;
  color: #222;
}

.hero-text h2 {
  margin-top: 0;
  font-size: 1.8rem;
}

.hero-buttons {
  margin-top: 1rem;
}

.hero-buttons a {
  display: inline-block;
  margin-right: 1rem;
  padding: 0.6rem 1.2rem;
  background-color: #007ACC;
  color: #fff;
  text-decoration: none;
  border-radius: 6px;
  font-weight: bold;
  transition: background 0.3s ease;
}

.hero-buttons a:hover {
  background-color: #005fa3;
}

@media (max-width: 768px) {
  .hero-container {
    flex-direction: column;
    text-align: center;
    padding: 1.5rem;
  }

  .hero-image {
    margin-bottom: 1rem;
    width: 160px;
  }

  .hero-text {
    margin-left: 0;
  }

  .hero-buttons a {
    margin-bottom: 0.5rem;
  }
}
</style>

<div class="hero-container">
  <img class="hero-image" src="/assets/logos/Nags.jpg" alt="Nagaraju Gaddam">
  <div class="hero-text">
    <h2>Welcome to Nags Climate</h2>
    <p>
      Cities are the heartbeat of our climate future. My work explores how urban environments interact with extreme weather—like heatwaves and floods—to build data-driven, equitable, and resilient urban systems.
    </p>
    <p>
      Using modeling, remote sensing, and science for policy, I aim to bridge knowledge and action across research and society.
    </p>
    <div class="hero-buttons">
      <a href="https://nagsclimate.github.io/about/">Learn More</a>
      <a href="https://nagsclimate.github.io/join-us/">Join Us</a>
    </div>
  </div>
</div>
