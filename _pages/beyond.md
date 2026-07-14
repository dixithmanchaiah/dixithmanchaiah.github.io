---
layout: page
title: Beyond Research
permalink: /beyond-research/
nav: true
nav_order: 4
---

*Research is an important part of my life, but not the whole of it. This page is a collection of books, places, and experiences that have shaped my perspective beyond the laboratory.*

---

# Reading

## Currently Reading

- **The Krishna Key** — *Ashwin Sanghi*

## Recently finished

- **Illuminate Your Truth** — A practical guide to personal growth, focusing on techniques such as breathwork, mindfulness, meditation, and journaling to cultivate greater self-awareness and emotional well-being.

- **The Secret of the Nagas** — Revisited Amish Tripathi's *Shiva Trilogy*. I appreciate the way Shiva is portrayed as a deeply human character rather than an infallible deity. The narrative, combined with its vivid journey across the landscapes, history, and mythology of India, makes it an engaging and memorable read.

---

# Travel

Exploring new places is one of my favorite ways to disconnect, recharge, and experience different landscapes and cultures.

## Recent travel to Badlands National Park

One of the most striking landscapes I have visited, with layered rock formations and vast open scenery.
<div class="row">
{% for image in site.static_files %}
  {% if image.path contains '/assets/img/recent/' %}
    {% unless image.path contains '-400' or image.path contains '-800' or image.path contains '-1200' or image.path contains '.webp' %}
      <div class="col-sm-4">
        {% include figure.liquid 
            path=image.path
            class="img-fluid rounded z-depth-1"
            zoomable=true
        %}
      </div>
    {% endunless %}
  {% endif %}
{% endfor %}
</div>

---

# Gallery

A small collection of moments and places that I found worth capturing.
<div class="row">
{% for image in site.static_files %}
  {% if image.path contains '/assets/img/gallery/' %}
    {% unless image.path contains '-400' or image.path contains '-800' or image.path contains '-1200' or image.path contains '.webp' %}
      <div class="col-sm-4">
        {% include figure.liquid 
            path=image.path
            class="img-fluid rounded z-depth-1"
            zoomable=true
        %}
      </div>
    {% endunless %}
  {% endif %}
{% endfor %}
</div>

