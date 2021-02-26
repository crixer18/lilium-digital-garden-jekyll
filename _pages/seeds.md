---
title: Notes
layout: blog
---

# Seeds

## This is an index of your notes


>Questo è un belockquote fatto in markdwn- Donec nisl metus, aliquam quis nulla et, laoreet gravida dolor. Sed faucibus diam dolor, at egestas neque auctor ac. Integer gravida mollis tincidunt. Proin auctor auctor nisl non posuere. Vestibulum luctus ultricies diam, eu tempus urna ultricies nec. Curabitur luctus, risus in scelerisque cursus, dolor odio ornare lacus, eu commodo quam orci at dui. Maecenas ornare elementum mollis. Nunc ac congue erat. Morbi eu sapien a urna vulputate molestie. Maecenas accumsan leo a enim imperdie

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