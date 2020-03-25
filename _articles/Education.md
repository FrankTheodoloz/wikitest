---
layout: page
following: _articles/tagging-101.md
title: "Custom subject"
key: custom
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

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.