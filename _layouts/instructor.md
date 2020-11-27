---
layout: default
---
{% if page.image %}
<img class="instructor-image" src="{{ page.image }}">
{% endif %}

<h1>{{ page.name }}</h1>

{{ content }}