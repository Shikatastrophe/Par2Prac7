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

## Jonathan-Z

{% for jonathanz in collections.jonathanz %}

- [{{jonathanz.data.title}}]({{ jonathanz.url | url }})

{% endfor %}

## Samuel

{% for samuel in collections.samuel %}

- [{{samuel.data.title}}]({{ samuel.url | url }})

{% endfor %}