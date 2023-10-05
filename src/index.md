---
layout: base.njk
title: Alumnos
---
<img src="{{ '/static/img/Logo.jpg' | url }}" align="left" width="40">

# Universidad Amerike

## Licenciatura en Ingeniería de Desarrollo De Software Interactivo y Videojuegos

### Programación en Lenguajes Interpretados

### Profesor - Jonathan Mircha

# {{ title }}
<br>
<br>
<div></div>

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

## Andre Cerdan

{% for meg in collections.meg %}

- [{{meg.data.title}}]({{ meg.url | url }})

{% endfor %}

## Diego Lecanda

{% for lecanda in collections.lecanda %}

- [{{lecanda.data.title}}]({{ lecanda.url | url }})

{% endfor %}

## Hector Otero

{% for hector in collections.hector %}

- [{{hector.data.title}}]({{ hector.url | url }})

{% endfor %}

## Jonathan Pacheco

{% for Jonathan in collections.JonathanPacheco %}

- [{{Jonathan.data.title}}]({{ Jonathan.url | url }})

{% endfor %}

## Mario Pérez

{% for Mario in collections.Mario %}

- [{{Mario.data.title}}]({{ Mario.url | url }})

{% endfor %}

## Jose Andres Rodriguez Chirino

{% for vicio in collections.vicio %}

- [{{vicio.data.title}}]({{ vicio.url | url }})

{% endfor %}