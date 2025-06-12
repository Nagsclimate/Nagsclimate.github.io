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
.overlay-content {
  position: absolute;
  top: 20%;
  left: 5%;
  display: flex;
  align-items: center;
  z-index: 10;
  width: 90%;
  max-width: 1200px;
  color: white;
}

.overlay-content img {
  width: 180px;
  height: auto;
  border-radius: 10px;
  margin-right: 2rem;
  box-shadow: 0 4px 12px rgba(0,0,0,0.5);
}

.overlay-text h1 {
  font-size: 2.2rem;
  margin-bottom: 0.5rem;
}

.overlay-text p {
  font-size: 1.1rem;
  margin-bottom: 1rem;
  max-width: 700px;
  line-height: 1.6;
}

.overlay-buttons a {
  display: inline-block;
  margin-right: 1rem;
  padding: 0.6rem 1.2rem;
  background-color: rgba(255,255,255,0.1);
  color: white;
  text-decoration: none;
  border: 1px solid white;
  border-radius: 6px;
  font-weight: bold;
  transition: background 0.3s ease, color 0.3s ease;
}

.overlay-buttons a:hover {
  background-color: white;
  color: #000;
}

@media (max-width: 768px) {
  .overlay-content {
    flex-direction: column;
    align-items: flex-start;
    top: 15%;
  }

  .overlay-content img {
    margin-bottom: 1rem;
    width: 150px;
  }

  .overlay-text h1 {
    font-size: 1.8rem;
  }

  .overlay-text p {
    font-size: 1rem;
  }

  .overlay-buttons a {
    margin-bottom: 0.5rem;
  }
}
</style>

<div class="overlay-content">
  <img src="/assets/logos/Nags.jpg" alt="Nags">
  <div class="overlay-text">
    <h1>Welcome to Nags Climate</h1>
    <p>
      Exploring how cities shape and are shaped by climate extremes. My work connects science with society to help build resilient, just, and data-driven urban futures.
    </p>
    <div class="overlay-buttons">
      <a href="https://nagsclimate.github.io/about/">Learn More</a>
      <a href="https://nagsclimate.github.io/join-us/">Join Us</a>
    </div>
  </div>
</div>
