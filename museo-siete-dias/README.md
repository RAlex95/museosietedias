# Museo de los Siete Días

Una página web con forma de museo pequeño. Siete salas, una por cada día.
Cada sala es una cartela de museo: título, fecha, localización, técnica,
ficha y nota del comisario. La sala VIII está cerrada y se abre al visitar
las siete anteriores.

Es un regalo personal. No es una plantilla ni un proyecto reutilizable.

## Abrirlo

Es un único fichero sin dependencias ni build. Basta con abrir
[`index.html`](index.html) en cualquier navegador.

Las dos únicas cosas que carga de fuera son las tipografías (Bodoni Moda y
Archivo, desde Google Fonts). Sin ellas sigue funcionando: cae a las
tipografías del sistema.

## Detalles técnicos

- HTML, CSS y JavaScript a pelo. Sin librerías.
- Las salas se definen en el array `SALAS` del script, al final del fichero.
  La sala final es el objeto `FINAL`.
- Las salas visitadas se guardan en `localStorage` del navegador. Cada
  visitante tiene su propio recorrido y nada sale del dispositivo.
- Diseño pensado para móvil primero. Un solo tema: oscuro.
