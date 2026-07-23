---
layout: default
title: Main Quests
permalink: /main-quests/
---

# Main Quests

Full main-quest easter-egg walkthroughs for every Black Ops 1 / 2 / 3 map.
Fewer clicks, image-based steps, no videos to scrub through.

<div class="guides-grid">
{% for egg in site.data.eggs %}
  {% include guide-card.html egg=egg %}
{% endfor %}
</div>
