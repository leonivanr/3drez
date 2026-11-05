# 3drez

Ajedrez sobre las seis caras de un cubo. Cada cara es un tablero de 4×4 y las piezas siguen en la cara vecina cuando cruzan un borde.

## Cómo se juega

- Arrastrá para girar el cubo y pellizcá para acercarte.
- **Para ganar, comé a todos los peones rojos** con tu pieza dorada.
- Los niveles van de la pieza más fácil a la más difícil: Reina → Torre → Alfil → Caballo.
- Las rocas bloquean el camino.
- Si resolvés el nivel en el mínimo de jugadas posible, ganás tres estrellas.

## Reglas del cubo

- **Torre:** en línea recta; al cruzar un borde sigue en la cara vecina.
- **Alfil:** en diagonal; la diagonal se corta en las esquinas del cubo, donde se juntan tres caras.
- **Caballo:** salta en L; puede caer en otra cara, pero no puede saltar a través de una esquina.
- **Reina:** combina torre y alfil.
- Una casilla teñida de rojo avisa que hay un rival en la cara opuesta, en la misma posición.

## Tecnología

Un solo archivo `index.html` con [Three.js](https://threejs.org/) (r128, cargado desde cdnjs). No necesita instalación ni compilación: abrí `index.html` en el navegador o publicalo con GitHub Pages.
