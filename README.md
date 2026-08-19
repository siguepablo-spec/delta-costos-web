# DELTA · pantalla

Pantalla del sistema de costos del Taller DELTA.

Es **solo la pantalla**: acá no hay datos ni claves. Los datos viven en una
planilla de Google y se piden a una web app de Apps Script, que exige una clave
que no está en este repositorio.

No se edita a mano. Se genera desde el proyecto de Apps Script con:

    node build-web.js

Cualquier cambio hecho acá se pierde en la próxima generación.
