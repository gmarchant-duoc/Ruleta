# Ruleta de exposiciones Duoc UC

Aplicación web para sortear el orden de exposición de un curso. Funciona en el navegador, sin instalar dependencias ni levantar un servidor.

## Cómo usarla

1. Descarga o clona el repositorio y abre [index.html](ruleta-exposiciones/dist/index.html) en tu navegador. Mantén el archivo junto a las imágenes de la carpeta `dist`.
2. Escribe un nombre en cada campo. Usa **Agregar opción** para sumar participantes o pega una lista con un nombre por línea en el primer campo.
3. Pulsa **Generar rueda** y luego **¡Girar ahora!** para asignar un puesto. El puntero queda sobre la opción sorteada y el resultado aparece en **Orden de exposición**.
4. Gira hasta completar el orden. Cada opción participa una sola vez por sorteo. **Reiniciar sorteo** limpia el orden y vuelve a habilitar la lista original.

Los nombres y resultados se procesan en el navegador y se pierden al recargar o cerrar la pestaña.

## Archivos

- [index.html](ruleta-exposiciones/dist/index.html) contiene la interfaz, los estilos y la lógica del sorteo. Usa Canvas para dibujar la rueda y `crypto.getRandomValues()` para elegir entre las opciones pendientes.
- [duoc.svg](ruleta-exposiciones/dist/duoc.svg) contiene el logo de Duoc UC. [Origen en Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Logo_DuocUC.svg).
- [pasillo.png](ruleta-exposiciones/dist/pasillo.png) es un recorte de la imagen de referencia del diseño.
