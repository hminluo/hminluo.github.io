---
layout: archive
permalink: /scribbles/
title: "Scribbles"
author_profile: true
---

<ul style="list-style-type:none">
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    </li>
  {% endfor %}
</ul>
