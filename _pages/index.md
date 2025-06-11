---
layout: splash
permalink: /
title: "The Urban Planet Lab"
header:
  overlay_image: /assets/city-pics/Bologna.jpeg
  overlay_filter: 0.6
  caption: "Photo credit: [**Nags**](https://unsplash.com)"
  actions:
    - label: "Learn More"
      url: "/about/"
    - label: "Join Us"
      url: "/join-us/"
---

<div style="display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; padding: 2rem 0;">

  <!-- Left side: Welcome text -->
  <div style="flex: 1 1 500px; max-width: 600px; padding-right: 2rem;">
    <h2 style="margin-top: 0;">Welcome</h2>
    <p style="font-size: 1.1rem; line-height: 1.6;">
      Welcome to my website—a space where science meets cities, and climate meets community.<br><br>
      As urbanization intensifies, cities are becoming the frontlines of our planet’s greatest environmental challenges—from extreme heat to flooding and inequality. My research explores how urban environments and extreme weather interact, using tools like numerical weather modeling, remote sensing, and data science to build resilient and equitable cities.
    </p>
    <p style="font-size: 0.95rem; color: #666;">
      <strong id="datetime"></strong>
    </p>
    <script>
      document.getElementById("datetime").innerText = new Date().toLocaleString();
    </script>

    <!-- Social Links -->
    <div style="margin-top: 1rem;">
      <a href="https://twitter.com/yourhandle" target="_blank">
        <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white">
      </a>
      <a href="https://github.com/yourhandle" target="_blank">
        <img src="https://img.shields.io/badge/GitHub-333?style=for-the-badge&logo=github&logoColor=white">
      </a>
      <a href="https://linkedin.com/in/yourhandle" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
      </a>
    </div>
  </div>

  <!-- Right side: Image -->
  <div style="flex: 0 1 300px; text-align: center;">
    <img src="/assets/images/nags.jpg" alt="Nagaraju Gaddam" style="max-width: 100%; border-radius: 8px; box-shadow: 0 0 12px rgba(0,0,0,0.1);">
  </div>

</div>

<!-- Optional scrolling tagline -->
<div style="margin-top: 2rem; padding: 1rem; background: #f9f9f9; font-size: 1rem; overflow: hidden; white-space: nowrap;">
  <div style="display: inline-block; animation: scroll-left 15s linear infinite;">
    🌍 Urban Heat • 📡 Remote Sensing • 🛰️ Climate Justice • 📘 Atmospheric Modeling • 🤝 Collaboration
  </div>
</div>
<style>
  @keyframes scroll-left {
    0% { transform: translateX(100%); }
    100% { transform: translateX(-100%); }
  }
</style>

{% include feature_row %}