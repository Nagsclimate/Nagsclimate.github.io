---
layout: single
classes: wide
sitemap: true
permalink: /creative-space/blog-stories/
author_profile: true
title: "Blog & Stories"
gallery:
  - url: /assets/images/blog1.jpg
    image_path: /assets/images/blog1.jpg
    alt: "Blog story image 1"
    title: "Story Highlight 1"
  - url: /assets/images/blog2.jpg
    image_path: /assets/images/blog2.jpg
    alt: "Blog story image 2"
    title: "Story Highlight 2"
---

# Blog & Stories

Welcome to the blog & stories section of Creative Space! Here, you'll find a variety of articles, personal narratives, and reflections.

{% for post in site.posts %}
  {% if post.category == 'blog-stories' %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
  </article>
  {% endif %}
{% endfor %}

