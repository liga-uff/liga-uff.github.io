---
layout: default
title: Comitê Gestor
---

{% for person in site.people %}
- [{{ person.name }}]({{ person.url }}) – {{ person.role }}
{% endfor %}
