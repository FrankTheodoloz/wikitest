---
layout: page
following: _articles/tagging-101.md
title: "Transports et mobilité"
key: transports-et-mobilite
is_main: true
toc:
- "Contexte"
- "Activités"
- "Mots clés"
---

### Contexte

Texte

### Activités

<ul>
  {% for activity in site.articles %}
    {%if activity.key == page.key %}
      {%if activity.id != page.id %}
  <li>
    <a href="{{site.baseurl}}{{ activity.url }}">
      {{ activity.title }}
    </a>
  </li>
      {% endif %}
    {% endif %}
  {% endfor %}
</ul>

### Mots clés

Texte