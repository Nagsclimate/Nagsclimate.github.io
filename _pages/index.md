---
layout: splash
permalink: /
title: ""
classes: wide
header:
  overlay_image: assets/city-pics/Bologna.jpeg
  overlay_filter: 0.55
  caption: "Photo credit: [**Nagssh**](https://unsplash.com)"
---
<style>
.hero-overlay {
  position: absolute;
  top: 15%;
  left: 50%;
  transform: translateX(-50%);
  width: 90%;
  max-width: 1100px;
  display: flex;
  align-items: center;
  color: white;
  z-index: 10;
  font-family: 'Segoe UI', sans-serif;
}

.hero-overlay img {
  width: 180px;
  height: auto;
  border-radius: 12px;
  margin-right: 2.5rem;
  box-shadow: 0 4px 16px rgba(0,0,0,0.4);
}

.hero-text h1 {
  font-size: 2.4rem;
  margin-bottom: 1rem;
}

.hero-text p {
  font-size: 1.15rem;
  line-height: 1.6;
  max-width: 600px;
  margin-bottom: 1.5rem;
}

.hero-buttons a {
  display: inline-block;
  margin-right: 1rem;
  padding: 0.6rem 1.3rem;
  border-radius: 6px;
  border: 1px solid white;
  color: white;
  text-decoration: none;
  font-weight: bold;
  background: rgba(255,255,255,0.05);
  transition: 0.3s ease;
}

.hero-buttons a:hover {
  background: white;
  color: black;
}

.scroll-down {
  position: absolute;
  bottom: 20px;
  left: 50%;
  transform: translateX(-50%);
  color: white;
  font-size: 1rem;
  animation: bounce 2s infinite;
  z-index: 10;
}

@keyframes bounce {
  0%, 100% { transform: translateX(-50%) translateY(0); }
  50% { transform: translateX(-50%) translateY(-10px); }
}

@media (max-width: 768px) {
  .hero-overlay {
    flex-direction: column;
    top: 10%;
    text-align: center;
  }

  .hero-overlay img {
    margin: 0 0 1.5rem 0;
    width: 140px;
  }

  .hero-text h1 {
    font-size: 1.9rem;
  }

  .hero-text p {
    font-size: 1.05rem;
  }

  .hero-buttons a {
    margin-bottom: 0.5rem;
  }
}
</style>

<div class="hero-overlay">
  <img src="/assets/logos/Nags.jpg" alt="Nags Gaddam">
  <div class="hero-text">
    <h1>Welcome to Nags Climate</h1>
    <p>
      I explore how cities shape and are shaped by climate extremes. By blending science, technology, and policy, my goal is to build data-driven, resilient, and just urban futures in a warming world.
    </p>
    <div class="hero-buttons">
      <a href="/about/">Learn More</a>
      <a href="/join-us/">Join Us</a>
    </div>
  </div>
</div>

<div class="scroll-down">
  ↓ Scroll to explore
</div>
