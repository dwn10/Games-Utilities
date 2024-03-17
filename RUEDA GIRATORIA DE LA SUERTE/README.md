
## Ruleta de la suerte virtual

- La ruleta está dividida en ocho secciones iguales, cada una con un nombre diferente (D.P, A.Y, etc.).

- Cuando se hace clic en el botón "spin" (girar), la ruleta gira aleatoriamente. El código utiliza JavaScript para generar un número aleatorio y aplicar una rotación correspondiente a la ruleta.

## Estructura del código:

## HTML:
- Define el título de la página como "Rueda giratoria de la suerte".
- Crea un contenedor principal `(div)` que contiene el botón para girar y la ruleta.
  - El botón `(div con clase spinBtn)` tiene el texto "girar".
  - La ruleta `(div con clase wheel)` contiene ocho segmentos `(div con clase name)`.
    - Cada segmento tiene un color de fondo personalizable y muestra un texto que se puede modificar `(span)`.
    - 
## CSS:
- Define los estilos generales del código (colores, fuentes, márgenes, etc.).
- Establece el estilo del contenedor principal, el botón y la ruleta.
- Da formato a los segmentos individuales de la ruleta (colores, tamaño de fuente, etc.).
  
## JavaScript:
- Selecciona el botón y la ruleta del HTML utilizando JavaScript.
- Genera un número aleatorio para simular el giro de la ruleta.
- Define una función que se activa al hacer clic en el botón.
- La función aplica una transformación de rotación a la ruleta utilizando el número aleatorio generado.
