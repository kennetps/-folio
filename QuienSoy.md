---
layout: page
permalink: /QuienSoy/
title: Quien soy?
description: Otros detalles interesantes respecto a mi!
---

<ul class="post-list">
{% for poem in site.poetry reversed %}
    <li>
        <h2><a class="poem-title" href="{{ poem.url | prepend: site.baseurl }}">{{ poem.title }}</a></h2>
      </li>
{% endfor %}
</ul>

