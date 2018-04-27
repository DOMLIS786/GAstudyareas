---
title: Russell House
layout: base
headline: Welcome to Russell House!
picture: /russell-house.jpg
---

<article>

  {% if page.picture %}
    <img src="{{ page.picture }}" alt="Photo of a {{ page.title | downcase }}">
  {% endif %}

  <h1>Profile: {{ page.title }}</h1>

  <div>
    {{ content }}
  </div>
  
</article>