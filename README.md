# Celebrity Fiestas — fragmento HTML para WPBakery

Fragmento listo para pegar dentro de un módulo **HTML Puro** de WPBakery. El archivo `index.html` contiene únicamente el contenido que debe insertarse dentro del body: no incluye `html`, `head`, header ni footer.

El CSS está incluido dentro de una etiqueta `<style>` en el mismo archivo. No hace falta agregar una hoja de estilos externa.

## Parallax y animaciones

Las imágenes ahora están separadas en capas `.celebrity-bg` y se animan con `animation-timeline: view()` y `animation-range`, la API CSS moderna de **Scroll-Driven Animations**. Los textos tienen una animación independiente de entrada, desplazamiento y opacidad. No se utiliza JavaScript. En navegadores que todavía no soportan `animation-timeline`, las imágenes y textos conservan una presentación estática legible como fallback.

## Tipografías

Se cargan mediante `@import` dentro del CSS inline: **Dosis 900** para títulos y **Lato** para subtítulos y textos.
