---
layout: page
title: Beyond Research
permalink: /beyond-research/
nav: true
nav_order: 4
---
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/glightbox/dist/css/glightbox.min.css">

<script src="https://cdn.jsdelivr.net/npm/glightbox/dist/js/glightbox.min.js"></script>

*Research is an important part of my life, but not the whole of it. This page is a collection of books, places, and experiences that have shaped my perspective beyond the laboratory.*

---

## Reading

### Currently Reading

- **The Krishna Key** — *Ashwin Sanghi*

### Recently Finished

- **Illuminate Your Truth** — A practical guide to personal growth, focusing on techniques such as breathwork, mindfulness, meditation, and journaling to cultivate greater self-awareness and emotional well-being.

- **The Secret of the Nagas** — Revisited Amish Tripathi's *Shiva Trilogy*. I appreciate the way Shiva is portrayed as a deeply human character rather than an infallible deity. The narrative, combined with its vivid journey across the landscapes, history, and mythology of India, makes it an engaging and memorable read.

---
## Gaming

Games have been a way to relax, explore stories, and appreciate creative world-building.

### Favorites

- **Assassin's Creed** — I enjoy the historical settings, exploration, and the blend of real-world events with fictional storytelling.

- **Super Smash Bros. Melee (SSBM)** — A game that stands out for its depth, mechanics, and enduring competitive community.

- **Tomb Raider** — Appreciated for its exploration, puzzles, and adventure-driven storytelling.

---

## Travel

Exploring new places is one of my favorite ways to disconnect, recharge, and experience different landscapes and cultures.

### Recent Travel — Badlands National Park

One of the most striking landscapes I have visited, with layered rock formations and vast open scenery.

<div class="row">
{% for image in site.static_files %}
  {% if image.path contains '/assets/img/recent/' %}
    {% unless image.path contains '-400' or image.path contains '-800' or image.path contains '-1200' or image.path contains '.webp' %}
      <div class="col-sm-4">
        <a href="{{ image.path | relative_url }}" class="glightbox">
          <img src="{{ image.path | relative_url }}" class="img-fluid rounded z-depth-1">
        </a>
      </div>
    {% endunless %}
  {% endif %}
{% endfor %}
</div>

---

## Gallery

A collection of moments and places worth capturing.

<div class="row">
{% for image in site.static_files %}
  {% if image.path contains '/assets/img/gallery/' %}
    {% unless image.path contains '-400' or image.path contains '-800' or image.path contains '-1200' or image.path contains '.webp' %}
      <div class="col-sm-4">
        <a href="{{ image.path | relative_url }}" class="glightbox">
          <img src="{{ image.path | relative_url }}" class="img-fluid rounded z-depth-1">
        </a>
      </div>
    {% endunless %}
  {% endif %}
{% endfor %}
</div>

---


