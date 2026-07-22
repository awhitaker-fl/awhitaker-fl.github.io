---
layout: default
title: Easter Egg Guides
---

# Zombies Easter Egg Hub

A streamlined hub for Call of Duty Zombies easter egg guides — built for
reference during live coop matches. Fewer clicks, image-based steps, no
videos to scrub through.

## Guides

<div class="guides-grid">
{% for egg in site.data.eggs %}
  {% include guide-card.html egg=egg %}
{% endfor %}
</div>
