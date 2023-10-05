---
layout: base.njk
title: Alumnos
---

# {{ title }}

Aqui los alumnos y su Nombre alv

## Víctor J. Chavarría

{% for kaseem in collections.kaseem %}

- [{{kaseem.data.title}}]({{ kaseem.url | url }})

{% endfor %}

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

## Amaury

{% for amaury in collections.amaury %}

- [{{amaury.data.title}}]({{ amaury.url | url }})

{% endfor %}

## Carol

{% for carol in collections.carol %}

- [{{carol.data.title}}]({{ carol.url | url }})

{% endfor %}

## Wilbert

{% for wil in collections.wil %}

- [{{wil.data.title}}]({{ wil.url | url }})

{% endfor %}

## Fernando

{% for fer in collections.fer %}

- [{{fer.data.title}}]({{ fer.url | url }})

{% endfor %}

## Victor Sanchez

{% for vic in collections.vic %}

- [{{vic.data.title}}]({{ vic.url | url }})

{% endfor %}

## Luis Lemus

{% for lemus in collections.lemus %}

- [{{lemus.data.title}}]({{ lemus.url | url }})

{% endfor %}