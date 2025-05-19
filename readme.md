# Análisis de Gustos Musicales - TensorFlow.js

Este sitio permite que un usuario califique distintas bandas musicales del 1 al 10, y en base a esas valoraciones, el sistema determina cuáles son los **géneros musicales preferidos** del usuario.

## Funcionalidad

- El usuario califica 6 bandas.
- Internamente, cada banda está asociada a uno o más géneros musicales (de forma oculta).
- Al hacer clic en **"Procesar Información"**, se calcula la afinidad del usuario con cada género mediante **multiplicación matricial**.
- Se muestra un ranking de géneros de mayor a menor afinidad.

## Tecnologías utilizadas

- HTML5 + JavaScript
- [TensorFlow.js](https://www.tensorflow.org/js) (vía CDN)

## Cómo usar

1. Descargar o abrir el archivo `index.html`.
2. Ingresar puntuaciones del 1 al 10 para cada banda.
3. Hacer clic en **Procesar Información**.
4. Se mostrará una lista ordenada con los géneros musicales que más te gustan.

> No requiere servidor ni instalación. Funciona directamente en el navegador.
