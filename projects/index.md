---
layout: page
title: Projects
---

<p> Projects made by students in our wonderful class. </p>

<ul class="entriespage">
  
  {% for post in site.tags.projects %}

 <li>
    <a href="{{ post.url }}">
      <h3>{{ post.title }}</h3>
    </a>
  </li>


  {% endfor %}

</ul>