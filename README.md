# Conversor Futurista de Imagen a WebP

Este es un conversor de imágenes a formato WebP, diseñado con una interfaz moderna y fácil de usar. Permite a los usuarios seleccionar una imagen, convertirla a formato WebP y descargarla con un solo clic.

## Características

- **Conversión a WebP**: Convierte imágenes en cualquier formato a WebP de manera rápida y eficiente.
- **Compresión Automática**: La imagen seleccionada se comprime automáticamente para asegurar un tamaño de archivo más pequeño sin perder calidad.
- **Vista previa**: Muestra una vista previa de la imagen convertida antes de descargarla.
- **Interfaz elegante**: Un diseño visualmente atractivo con transiciones suaves y efectos hover.
- **Responsive**: Optimizado para ser utilizado en dispositivos móviles y de escritorio.

## Tecnologías Usadas

- **HTML**: Estructura básica de la página web.
- **CSS**: Estilos personalizados para los botones, fondo, contenedores y más.
- **JavaScript**: Funcionalidades de conversión de imagen, compresión y gestión de la vista previa.
- **browser-image-compression**: Biblioteca para comprimir imágenes antes de la conversión.

## Instrucciones de Uso

1. **Selecciona una imagen**: Haz clic en el botón **"Seleccionar imagen"** para elegir una imagen desde tu dispositivo.
2. **Convierte a WebP**: Haz clic en el botón **"Convertir a WebP"** para iniciar la conversión.
3. **Vista previa y descarga**: Una vez convertida, la imagen WebP aparecerá como vista previa. También aparecerá un enlace para **"Descargar imagen WebP"**.
4. **Guardar la imagen**: Haz clic en el enlace de descarga para guardar la imagen convertida en tu dispositivo.

## Personalización

Puedes ajustar los colores, las fuentes y otros estilos modificando el archivo CSS. Las variables definidas en el `:root` permiten cambiar rápidamente los colores primarios, secundarios y de fondo:

```css
:root {
    --primary-color: #6c5ce7;
    --secondary-color: #00cec9;
    --bg-color: #0c0c1e;
    --text-color: #ffffff;
}
