---
title: Resources
layout: page
description: "Informasi tambahan seperti Poster dan Proposal penelitian"
image: assets/images/pic08.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

  <!-- Blog Posts Section -->
  <section id="blog">
    <div class="inner">
      <header class="major">
        <h2>Latest Resources Posts</h2>
      </header>
      
      <!-- Loop through posts -->
      <div class="posts">
        {% for post in site.posts %}
        <article>
          {% if post.image %}
          <a href="{{ post.url }}" class="image">
            <img src="{{ post.image }}" alt="{{ post.title }}">
          </a>
          {% endif %}
          <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
          <p>{{ post.excerpt | strip_html | truncate: 160 }}</p>
          <ul class="actions">
            <li><a href="{{ post.url }}" class="button">Read More</a></li>
          </ul>
        </article>
        {% endfor %}
      </div>
    </div>
  </section>

</div>
