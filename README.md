# Interceptor

Shooter en primera persona para navegador. Estás anclado sobre una plataforma en mitad del espacio y tienes que derribar los proyectiles que vienen hacia ti antes de que te alcancen. La dificultad sube cada 20 segundos.

## Cómo jugar

Abre `index.html` en cualquier navegador moderno (Chrome, Firefox, Edge). No necesita instalación; carga Three.js desde CDN, así que requiere conexión a internet.

| Control | Acción |
|---|---|
| Ratón | Apuntar |
| Clic | Disparar (mantén para ráfaga) |
| 1 / 2 | Glock 17 / Desert Eagle |
| F | Inspeccionar el arma |
| ESC | Pausa y ajustes |

En **Ajustes** puedes cambiar la sensibilidad, el campo de visión, el arma y personalizar la mira.

## Proyectiles

- **Normal** (nivel 1)
- **Rápido** (nivel 2): pequeño y veloz
- **Zigzag** (nivel 3): trayectoria errática
- **Blindado** (nivel 4): necesita 3 impactos de Glock o 1 de Desert Eagle
- **Divisor** (nivel 5): se parte en dos al destruirlo

## Tecnología

Un único archivo HTML con [Three.js](https://threejs.org/). Los modelos de las armas se generan por código y todos los sonidos se sintetizan con Web Audio, sin archivos externos.
