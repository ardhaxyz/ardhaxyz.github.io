---
layout: default
title: Home
description: Short biography and links
---

<section class="hero">
  <div class="hero-left">
    <h1 class="greeting">Hej, Ardha!</h1>

    <p class="bio">
      {{ site.bio | default: "With a background in Marine Science and a focus on data-driven policy analysis, I write about environment, economics, and minimal interfaces." }}
    </p>

    <ul class="meta-list">
      {% if site.education %}
        <li><strong>{{ site.education.date }}</strong> — {{ site.education.title }}</li>
      {% endif %}
    </ul>

    <nav class="social-inline" aria-label="Social links">
      {% include social-icons.html %}
    </nav>
  </div>

  <div class="hero-right" aria-hidden="false">
    {% if site.avatar %}
      <img class="avatar" src="{{ site.avatar | relative_url }}" alt="{{ site.author | default: "Ardha" }}">
    {% else %}
      <div class="avatar avatar-fallback" aria-hidden="true">{{ site.author | default: "A" | slice: 0 }}</div>
    {% endif %}
  </div>
</section>
