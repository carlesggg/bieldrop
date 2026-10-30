# Octágono 3D: MMA para 2 jugadores

Juego de MMA en 3D (three.js) para dos jugadores en el mismo teclado. Sin bots, sin servidor y sin build: es un sitio estático.

## Probar en local
Abre `public/index.html` en el navegador, o ejecuta `npx serve public`.

## Desplegar en Render desde GitHub
1. Sube esta carpeta a un repositorio de GitHub.
2. En Render: **New → Static Site** y conecta el repositorio.
3. **Build Command**: déjalo vacío. **Publish Directory**: `public`.
4. Pulsa **Create Static Site**. Cada `git push` redesplegará el juego.

También puedes usar **New → Blueprint** con el `render.yaml` incluido.

## Controles
Pulsa **H** dentro del juego para ver la tabla de controles de ambos jugadores.
