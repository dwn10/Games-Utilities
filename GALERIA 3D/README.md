
## Resumen:

La página web muestra un título con animación de neón que dice "Anwendungsentwicklung" (Desarrollo de aplicaciones) y un subtítulo que dice "Lehrgang 2023 - 2024" (Curso 2023 - 2024). Debajo del título, hay un carrusel giratorio que contiene 10 imágenes (1.jpg, 2.jpg, etc.).



## Elementos del código:

`body:` Define el estilo del cuerpo de la página web.
`h2.neon-text:` Define el estilo del título principal con animación de neón.
`h3:` Define el estilo del subtítulo.
`.box:` Define el estilo del carrusel que contiene las imágenes.
`.box span:` Define el estilo de cada imagen individual dentro del carrusel.

## Consideraciones:

El código usa prefijos de navegador web como `-webkit-` para garantizar la compatibilidad con navegadores antiguos.
El código no incluye funcionalidades interactivas.

## 1. Estilos generales CSS:
Establece márgenes y paddings a cero para todos los elementos.
Define la fuente predeterminada como 'Poppins', sans-serif.

## 2. Clase neon-text:
Aplica estilos a un elemento con la clase `neon-text.`
Lo posiciona en el centro absoluto de la pantalla.
Establece el texto en mayúsculas y con un tamaño de fuente de 5rem.
Define un cursor en forma de pointer al pasar el mouse por encima.
Crea un efecto de texto neón con color transparente y borde rojo mediante `-webkit-text-stroke.`
Anima el fondo con un degradado de rojo a negro que se mueve continuamente.

## 3. Efecto hover para neon-text:
Cambia el color del texto a `var(--color-red)` al pasar el mouse por encima.
Agrega sombras rojas para darle más profundidad al efecto neón.

## 4. Estilos para el body:
Centra el contenido de la página web horizontal y verticalmente.
Define una altura mínima del 100% del viewport.
Establece el color de fondo con la variable `--color-background.`

## 5. Etiqueta `<h3>`:
Posiciona la etiqueta `<h3>` en el centro absoluto de la página.
Centra el texto horizontalmente.
Define el tamaño de fuente a 1.9rem y el color con la variable `--color-secondary.`

## 6. Clase box:
Aplica estilos a los elementos con la clase `box.`
Define el tamaño del box a 12rem ancho y 12rem alto.
Aplica una animación que rota el elemento en perspectiva en 60 segundos.

## 7. Animación animate:
Define una animación que rota el elemento en Y de 0 grados a 360 grados en 60 segundos.

## 8. Clase .box span:
Aplica estilos a los elementos `<span>` que se encuentran dentro de los elementos con la clase `.box.`
Posiciona el elemento span de forma absoluta dentro del box.
Aplica otra animación que rota el elemento en Y en base al valor de la variable `--i` y lo traslada en el eje Z.
Agrega un efecto de reflejo en la parte inferior del elemento.

## 9. Imagen dentro de .box span:
Define estilos para las imágenes que se encuentran dentro de los elementos `<span>` de la clase `.box.`
La imagen ocupa todo el ancho y alto del elemento span.
