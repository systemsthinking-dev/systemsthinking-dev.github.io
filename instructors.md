---
title: Workshop Instructors
---

People

<div>
  {% for instructor in site.instructors %}
    <div>
      <h4><a href="{{ instructor.url }}">{{ instructor.name }}</a></h4>
      <p>{{ author.content | markdownify }}</p>
    </div>
  {% endfor %}
</div>