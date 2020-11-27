---
layout: default
---
{% if page.image %}
<img class="instructor-image" src="{{ page.image }}">
{% endif %}

<div>
<h1>{{ page.name }}</h1>
{% if page.twitter %}
<a href="{{ page.twitter}}">twitter</a>
{% endif %}
{% if page.site %}
<a href="{{ page.site}}">site</a>
{% endif %}
{% if page.blog %}
<a href="{{ page.blog}}">blog</a>
{% endif %}
</div>

{{ content }}