---
layout: base.njk
title: Alumnos
---

# {{ title }}

Aqui los alumnos y su Nombre alv

## Shika

{% for shika in collections.shika %}

- [{{shika.data.title}}]({{ shika.url | url }})

{% endfor %}