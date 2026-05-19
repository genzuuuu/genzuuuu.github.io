---
layout: default
title: Home
permalink: /
---

<div class="home-hero">
  <h1 class="home-name">{{ site.name }}</h1>
  <p class="home-role">{{ site.position }} · {{ site.affiliation }}</p>
  <p class="home-contact">
    <a href="mailto:{{ site.email }}">{{ site.email }}</a>
  </p>
  {% include social.html %}
</div>

<div class="home-intro">
  <p>
    Hi! I'm <strong>Gen Zu</strong>. I am a Ph.D. student at the
    <a href="https://www.cpfs.mpg.de/en/home" target="_blank" rel="noopener noreferrer">Max Planck Institute for Chemical Physics of Solids</a>
    in Dresden, Germany.
  </p>
  <p>
    My research focuses on the intersection of <strong>condensed matter physics</strong> and
    <strong>artificial intelligence</strong>, especially seeking new paradigms to describe
    quantum many-body systems.
  </p>
  <p>
    <a href="{{ '/about/' | relative_url }}">Read more about me →</a>
  </p>
</div>

<h2 class="section-heading">selected publications</h2>
{% include publications-list.html selected=true %}
<p class="section-more">
  <a href="{{ '/publications/' | relative_url }}">View all publications →</a>
</p>
