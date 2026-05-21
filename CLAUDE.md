# CLAUDE.md — Reglas del proyecto

## Stack permitido

- **Astro** como framework principal
- **Tailwind CSS** para estilos
- **JavaScript vanilla** para interactividad

## Restricciones estrictas

- **Sin TypeScript.** No crear ni modificar archivos `.ts` o `.tsx`. Si el proyecto ya tiene configuración de TS, ignorarla para código nuevo.
- **Sin librerías de animación.** Nada de GSAP, Framer Motion, Animate.css, AOS, ni similares. Las animaciones se hacen con CSS puro o Intersection Observer en JS vanilla.

## Comentarios

- Todos los comentarios en el código deben estar **en español**.

## Dependencias

- Antes de instalar cualquier dependencia nueva (`npm install`, `astro add`, etc.), **preguntar al usuario primero** y esperar confirmación explícita.

## Plan de cambios

- Antes de aplicar cualquier cambio que involucre múltiples archivos, mostrar un plan con **una línea por archivo** indicando qué se va a modificar. Esperar aprobación antes de proceder.
