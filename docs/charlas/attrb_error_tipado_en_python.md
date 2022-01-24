---
layout: post
title: AttributeError, 'Talk' object has no attribute 'title'
parent: Charlas
has_toc: false
---

# AttributeError: 'Talk' object has no attribute 'title'

## Información Básica

* Orador: Laski
* Duración: 40 min.
* Nivel: Medio (ideal: a gente que ya programó un poquito en Python)
* Etiquetas:  Desarrollo, Python, tipado

## Presentación

<iframe width="800px" height="480" src="https://www.youtube.com/embed/cUPcnv7zfrY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Links

* Falta foto de orador

## Bio:
Nahuel Lascano programa en Python hace 8 años pero siempre trata de estar al día con las últimas novedades del lenguaje. Trabaja desde hace dos años en Eryx, una cooperativa de desarrollo de software, horizontal y autogestionada.

## Descripción corta:
En esta charla vamos a hablar sobre la nueva sintaxis de anotaciones de tipos introducidos en Python 3 y extendidos en Python 3.5/3.6. Si alguna vez un AttributeError te agarró desprevenido, vení a escuchar cómo se puede prevenir sin tener que mudarte a un lenguaje estáticamente tipado.


## Descripción larga:
Una de las principales ventajas de Python es su sistema de tipado, conocido informalmente como “duck typing”: si un objeto sabe responder el mensaje quack() entonces el envío de ese mensaje no va a provocar un error. Esto acelera mucho el desarrollo y ayuda a construir modelos con bajo acoplamiento: implementar una interfaz en Python es tan simple como escribir los métodos que se esperan, sin heredar de nadie. Sin embargo, este sistema de tipado es también una gran causa de dolores de cabeza a la hora de programar: quién no se encontró un AttributeError: “‘Dog’ object has no attribute ‘quack''' en un código que creía perfecto. En esta charla buscamos introducir al público a la sintaxis de anotación de tipos introducida en Python 3, y su implementación efectiva con la librería typing disponible desde Python 3.5. La mayor parte de la bibliografía será la oficial (PEPs 483, 484, 526 y la documentación de typing), y usaremos también videos / código en vivo de la herramienta PyCharm y de mypy, que tienen soporte para anotaciones de tipos en tiempo de compilación.

