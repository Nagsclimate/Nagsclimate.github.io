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
.home-overlay {
  position: absolute;
  top: 15%;
  left: 10%;
  right: 10%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  color: white;
  z-index: 100;
  font-family: "Segoe UI", sans-serif;
}

.home-overlay .photo {
  flex: 1;
  padding-right: 2rem;
}

.home-overlay .photo img {
  width: 220px;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.4);
}

.home-overlay .text {
  flex: 2;
  max-width: 600px;
}

.home-overlay .text h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.home-overlay .text p {
  font-size: 1.1rem;
  line-height: 1.6;
  margin-bottom: 1.5rem;
}

.home-overlay .buttons a {
  margin-right: 1rem;
  padding: 0.6rem 1.2rem;
  border: 2px solid white;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  transition: 0.3s;
}

.home-overlay .buttons a:hover {
  background: white;
  color: black;
}

@media (max-width: 768px) {
  .home-overlay {
    flex-direction: column;
    text-align: center;
    top: 10%;
  }

  .home-overlay .photo {
    padding-right: 0;
    margin-bottom: 1.5rem;
  }

  .home-overlay .photo img {
    width: 160px;
  }

  .home-overlay .text h1 {
    font-size: 1.8rem;
  }

  .home-overlay .text p {
    font-size: 1rem;
  }
}
</style>

<div class="home-overlay">
  <div class="photo">
    <img src="/assets/logos/Nags.jpg" alt="Nagaraju Gaddam">
  </div>
  <div class="text">
    <h1>Welcome to Nags Climate</h1>
    <p>
      I work at the intersection of cities and climate—exploring how urban environments interact with extreme weather and social vulnerability. Using data, models, and science, I aim to help shape just and resilient cities for a warming world.
    </p>
    <div class="buttons">
      <a href="/about/">Learn More</a>
      <a href="/join-us/">Join Us</a>
    </div>
  </div>
</div>
