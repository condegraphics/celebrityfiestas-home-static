# Celebrity Fiestas — fragmento HTML para WPBakery

Fragmento listo para pegar dentro de un módulo **HTML Puro** de WPBakery. El archivo `index.html` contiene únicamente el contenido que debe insertarse dentro del body: no incluye `html`, `head`, header ni footer.

El CSS está incluido dentro de una etiqueta `<style>` en el mismo archivo. No hace falta agregar una hoja de estilos externa.

## Parallax

En escritorio se fuerza `background-attachment: fixed !important` dentro de una media query para dispositivos con mouse/puntero preciso. En móviles se mantiene `background-attachment: scroll`, que es el comportamiento más compatible y el que ya funciona correctamente en la web.

## Tipografías

Se cargan mediante `@import` dentro del CSS inline: **Dosis 900** para títulos y **Lato** para subtítulos y textos.
