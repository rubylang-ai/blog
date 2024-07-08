---
layout: default
---

{% for post in collections.progress.resources %}
  <h2>
    <a href="{{ post.relative_url }}">
      <img src="{{ post.image }}" align="left" width="300" />
      {{ post.title }}
    </a>
  </h2>
{% endfor %}
