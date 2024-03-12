# Proyecto creado con las siguientes tecnologías:

```javascript
const Projects = {
  	code: ["HTML", "CSS", "Javascript"],
	technologies: {
	devTool: ["Visual Studio Code"]
	}
}
```

## PUZZLE Descripción:
- Es un juego de colocación de imágenes en un tablero. para interactuar con un puzzle de Rubik digital que el usuario puede resolver arrastrando y soltando las casillas del puzzle.

## Secciones del código:
- Título: Muestra el título "PUZZLE RUBIK"
- Sección de arrastrar (drag):
-- Contiene nueve cuadros (div) con la clase dragBox.
-- Cada dragBox contiene un elemento div con la clase images que tiene una imagen representada por una URL.
-- La función drag se activa cuando un elemento images (una imagen) se arrastra. Guarda el identificador del elemento que se está arrastrando.

## Sección de soltar (board):
- Contiene nueve cuadros (div) con la clase dropBox.
- La función allowDrop se activa cuando se arrastra un elemento sobre un dropBox. Evita que se siga propagando el evento por el DOM.
- La función drop se activa cuando se suelta un elemento sobre un dropBox. Obtiene el identificador del elemento arrastrado y lo agrega como hijo del dropBox donde se soltó.

## Botón de reinicio:
- Un botón con la clase reset que al hacer clic recarga la página web y reinicia el puzzle.

## Comportamiento:
- El código permite arrastrar y soltar las imágenes del puzzle ubicadas en la sección izquierda (drag) hacia los cuadros vacíos de la sección derecha (board).
- Al cargar la página, las imágenes se desordenan aleatoriamente para que el usuario las ordene y complete el puzzle.