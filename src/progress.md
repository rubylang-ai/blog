---
layout: default
---

{% for post in collections.progress.resources %}
  <h2 class="post-list">
    <a href="{{ post.relative_url }}">
      <img src="{{ post.preview_image }}" align="left" width="300" />
      {{ post.title }}
    </a>
  </h2>
{% endfor %}
