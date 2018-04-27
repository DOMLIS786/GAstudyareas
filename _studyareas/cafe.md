---
title: Turner Cafe
layout: studyareas
headline: Welcome to Turner Cafe!
picture: /turner-cafe.jpg
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