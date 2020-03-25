---
layout: page
title: "Gouvernance numérique à GVA"
key: gouvernance-numerique-a-gva
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