---
layout: default
title: Home
description: Short biography and links
---

<section id="about" class="card intro-grid">
  <div class="intro-copy">
    <h2>Hello — I'm {{ site.author | default: "Ardha" }}</h2>

    <p class="bio">
      {{ site.bio | default: "I’m a researcher and writer interested in minimal interfaces, systems, and clarity. I build simple tools and write about design and engineering." }}
    </p>

    <p>
      <a class="btn-primary" id="subscribe" href="{{ site.substack | default: 'https://your-substack.substack.com' }}" target="_blank" rel="noopener">Read my Substack</a>
    </p>

    <div id="links" class="social-row" aria-label="Social links">
      {% include social-icons.html %}
    </div>
  </div>

  <div class="intro-avatar" aria-hidden="false">
    {% if site.avatar %}
      <img src="{{ site.avatar | relative_url }}" alt="{{ site.author | default: "Author" }}'s picture" class="avatar">
    {% else %}
      <div class="avatar avatar-fallback" aria-hidden="true">{{ site.author | default: "A" | slice: 0 }}</div>
    {% endif %}
  </div>
</section>
