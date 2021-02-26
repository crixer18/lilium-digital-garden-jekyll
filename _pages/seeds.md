---
title: Notes
layout: blog
---

# Seeds

## This is an index of your notes

* [Your First Note](../_notes/first-post.md)

<table class="seeds">
<ul>
  {% for note in site.notes %}
  <li style="list-style: none;">
    <a href="{{ note.url }}">
    <img class="seeds" src="{{ note.img }}" />
    <h3>{{ note.title }}</h3></a>
  </li>
  {% endfor %}
</ul>
</table>



<h1>Seeds</h1>

<div class="seed-preview">
  {% for note in site.notes %}
    <div class="titcol">
      <a href="{{ note.url }}"><h3>🌱 {{ note.title }}</h3></a>
      <p>{{ note.description }}</p>
      <div class="tags">
        <p>{{ note.tag }}</p>
      </div>
    </div>
    <!--<td class="imgcol">
      <a href="{{ note.url }}"><img class="seeds" src="{{ note.img }}" /></a>
    </td>-->
  {% endfor %}