---
layout: default
permalink: /
---
<div class="content">
  {% if site.front_img %}
  <img src="{{ site.front_img_path }}" id="fullscreen">
  {% endif %}

  {% if site.avatar %}
  <img src="{{ site.avatar_img_path }}" id="avatar">
  {% endif %}

  <h1>{{ site.name }}</h1>
  <h3>{{ site.description }}</h3>

  <ul>
    {% if site.github_username %}
    <li><a class="fa fa-2x fa-github" href="https://github.com/{{ site.github_username }}"><span class="description">GitHub</span></a></li>
    {% endif %}

    {% if site.facebook_username %}
    <li><a class="fa fa-2x fa-facebook" href="https://facebook.com/{{ site.facebook_username }}"><span class="description">Facebook</span></a></li>
    {% endif %}

    {% if site.instagram_username %}
    <li><a class="fa fa-2x fa-instagram" href="https://instagram.com/{{ site.instagram_username }}"><span class="description">Instagram</span></a></li>
    {% endif %}

    {% if site.email %}
    <li><a class="fa fa-2x fa-envelope" href="mailto:{{ site.email }}"><span class="description">Email</span></a></li>
    {% endif %}
  </ul>
</div>
