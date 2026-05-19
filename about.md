---
layout: default
title: About
permalink: /about/
---

<h1 class="page-title">About</h1>

<div class="about-grid">
  <div class="about-main">
    <p>
      Hi, my name's Gen and I'm currently a Ph.D. student at the
      Max Planck Institute for Chemical Physics of Solids in Dresden, Germany.
      My research interest focuses on the combination of
      <span class="mark">condensed matter physics</span> and
      <span class="mark">artificial intelligence</span>, especially seeking a new
      paradigm to describe quantum many-body physics systems.
    </p>
    <p>
      I am most skilled in: <span class="mark">Soulslike gaming</span> and
      <span class="mark">eating KFC</span>.
    </p>

    <h2 class="section-heading">interests</h2>
    <p>Alongside physics and machine learning, some of my hobbies are:</p>
    <ul>
      <li>Snowboarding</li>
      <li>Gaming</li>
      <li>Cooking</li>
    </ul>
    <p>
      Look at the most important partner I have on the planet, my cat, Phi:
    </p>
    <p>
      <img src="{{ '/images/phi.jpg' | relative_url }}" alt="Phi the cat" class="about-photo" style="max-width: 420px;">
    </p>
  </div>

  <aside class="about-sidebar">
    <img
      src="{{ site.profile_image | relative_url }}"
      alt="{{ site.name }}"
      class="about-photo"
    >
    {% include social.html %}
  </aside>
</div>
