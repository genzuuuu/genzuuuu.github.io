---
layout: default
title: About
permalink: /
---

<header class="post-header">
  <h1 class="home-name">{{ site.name }}</h1>
  <p class="home-role">{{ site.position }} · {{ site.affiliation }}</p>
</header>

<div class="about-grid about-page">
  <div class="about-main">
    <p>
      Hi! I'm <strong>{{ site.name }}</strong>. I am a Ph.D. student at the
      <a href="https://www.cpfs.mpg.de/en/home" target="_blank" rel="noopener noreferrer">{{ site.affiliation }}</a>
      in Dresden, Germany.
    </p>
    <p>
      My research focuses on the combination of
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
    <p>Look at the most important partner I have on the planet, my cat, Phi:</p>
    <p>
      <img src="{{ '/images/phi.jpg' | relative_url }}" alt="Phi the cat" class="about-inline-photo">
    </p>
  </div>

  <aside class="about-sidebar profile-card">
    <figure>
      <img
        src="{{ site.profile_image | relative_url }}"
        alt="{{ site.name }}"
        class="about-photo"
      >
    </figure>
    <div class="profile-more-info">
      <p>{{ site.name }}</p>
      <p><a href="mailto:{{ site.email }}">{{ site.email }}</a></p>
    </div>
    {% include social.html %}
  </aside>
</div>

<h2 class="section-heading">
  <a href="{{ '/publications/' | relative_url }}">selected publications</a>
</h2>
{% include publications-list.html selected=true preview=true %}
<p class="section-more">
  <a href="{{ '/publications/' | relative_url }}">View all publications →</a>
</p>

<h2 class="section-heading">
  <a href="{{ '/experience/' | relative_url }}">experience</a>
</h2>
{% include experience-entries.html %}

<h2 class="section-heading">
  <a href="{{ '/education/' | relative_url }}">education</a>
</h2>
{% include education-entries.html %}
