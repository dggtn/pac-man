# Pac-Man en JavaScript

## Descripción del Proyecto

Este proyecto es una implementación del clásico juego **Pac-Man**, desarrollado usando **JavaScript**, **HTML**, y **CSS**. En este juego, los jugadores controlan a Pac-Man para que coma los puntos en un laberinto, mientras evitan ser atrapados por los fantasmas. El objetivo es comer todos los puntos del laberinto sin ser tocado por los fantasmas.

### Características Principales:

- **Juego interactivo**: Jugabilidad en tiempo real, con control de Pac-Man utilizando las teclas de dirección.
- **Fantasmas**: Los fantasmas se mueven en el laberinto con patrones predefinidos y persiguen a Pac-Man.
- **Puntos**: El jugador debe comer todos los puntos del laberinto para completar el nivel.
- **Niveles**: El juego tiene varios niveles, con dificultad progresiva.
- **Sonidos**: Efectos de sonido cuando Pac-Man come puntos o es atrapado por un fantasma.

## Tecnologías Utilizadas

- **JavaScript**: Lenguaje principal para la lógica del juego, control de eventos y animaciones.
- **HTML5**: Estructura básica de la página web y la creación de elementos del juego.
- **CSS3**: Estilo y diseño visual del juego, incluidos los colores, el fondo y la disposición de los elementos.
- **Canvas (HTML5)**: Usado para renderizar los gráficos del juego en 2D (el laberinto, los personajes, etc.).

## Instrucciones de Instalación

Para ejecutar este proyecto en tu máquina local, sigue estos pasos:

### 1. Clonar el Repositorio

Clona este repositorio en tu máquina local con el siguiente comando:

```bash
git clone https://github.com/tu_usuario/pacman-javascript.git
2. Acceder a la Carpeta del Proyecto
Entra en el directorio donde se clonó el proyecto:

bash
Copiar código
cd pacman-javascript
3. Ejecutar el Proyecto
No necesitas ninguna instalación adicional ni servidor para ejecutar este juego. Simplemente abre el archivo index.html en tu navegador para jugar:

bash
Copiar código
open index.html   # En MacOS
start index.html  # En Windows
4. Control de Juego
Puedes controlar a Pac-Man utilizando las siguientes teclas:

Flecha arriba: Mover hacia arriba.
Flecha abajo: Mover hacia abajo.
Flecha izquierda: Mover hacia la izquierda.
Flecha derecha: Mover hacia la derecha.
5. Objetivo del Juego
El objetivo es comer todos los puntos del laberinto sin ser atrapado por los fantasmas. Cuando todos los puntos son comidos, avanzas al siguiente nivel.

Demo
Puedes ver una demostración en vivo del juego en el siguiente enlace:

Demostración en Vivo

Estructura del Proyecto
bash
Copiar código
pacman-javascript/
├── index.html      # Página principal con el lienzo (canvas) del juego
├── style.css       # Estilos del juego (laberinto, personajes, etc.)
├── game.js         # Lógica del juego: movimiento de Pac-Man, fantasmas y puntuación
└── assets/         # Carpeta con imágenes y sonidos del juego
  ├── pacman.png  # Imagen de Pac-Man
  ├── ghost.png   # Imagen de los fantasmas
  ├── eat.wav     # Sonido cuando Pac-Man come un punto
  └── caught.wav  # Sonido cuando Pac-Man es atrapado
Cómo Funciona el Juego
El juego se basa en un lienzo HTML5 (<canvas>) donde se dibujan los diferentes elementos del juego. La lógica del movimiento de Pac-Man y los fantasmas se controla a través de JavaScript. La animación del movimiento y las interacciones del jugador se gestionan mediante el uso de requestAnimationFrame.

Pac-Man: Se mueve con las teclas de dirección y tiene como objetivo comer todos los puntos en el laberinto.
Fantasmas: Se mueven de forma automática dentro del laberinto, siguiendo patrones predefinidos.
Puntos: Los puntos se distribuyen a lo largo del laberinto, y Pac-Man debe comerlos para avanzar.
Desafíos y Mejoras Futuras
Este proyecto es una implementación básica de Pac-Man, y hay varias mejoras que se pueden hacer:

Inteligencia Artificial para los fantasmas: Implementar diferentes comportamientos para los fantasmas (como "seguir" o "huir" de Pac-Man).
Poderes especiales: Agregar elementos especiales como cerezas o pastillas de poder que cambian el comportamiento de los fantasmas.
Niveles adicionales: Agregar más niveles con laberintos más complejos.
Sonidos adicionales: Añadir más efectos de sonido y música de fondo.
Puntuación y almacenamiento: Implementar un sistema de puntuación que se guarde en el navegador o en un servidor.
Contribuciones
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

Haz un fork del repositorio.
Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
Realiza tus cambios y haz commit (git commit -am 'Agrega nueva funcionalidad').
Empuja los cambios a tu repositorio (git push origin feature/nueva-funcionalidad).
Abre un pull request en el repositorio original.
Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

