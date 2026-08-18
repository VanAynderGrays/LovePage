# Para Wuillianner ♥

Página de amor de un solo archivo (`index.html`), pensada para abrirse desde el
celular al escanear un código QR.

## Qué trae

- Portada con corazón que late: ella toca y se abre la sorpresa.
- Cielo estrellado animado con estrellas fugaces (canvas) y auroras de fondo.
- Su nombre con degradado brillante, carta en tarjeta de vidrio, razones,
  contador de tiempo en vivo y frases que se escriben solas.
- Jardín de flores dibujadas a mano en SVG: **tres capas de pétalos** por flor,
  con floración escalonada, tallos que se mecen, hierba y luciérnagas.
- Pétalos cayendo, corazones al tocar la pantalla y firma **-AE** en el pie.
- Todo mobile-first, sin dependencias (solo tipografías de Google Fonts).

## Qué puedes cambiar (todo está comentado en el archivo)

| Dónde | Qué es |
|---|---|
| `<!-- EDITABLE: TU CARTA -->` | Los párrafos de la carta |
| `<!-- EDITABLE: agrega o quita bloques .razon -->` | Las razones por las que la amas |
| `CONFIG.fechaInicio` | Desde qué fecha cuenta el contador |
| `CONFIG.frases` | Las frases que se escriben solas al final |
| `<p class="firma">-AE</p>` | La firma del pie |
| `:root { --lila, --rosa, ... }` | La paleta de colores |

## Cómo llevarla al QR

Un QR no puede guardar una página completa (le caben pocos cientos de
caracteres), así que lo correcto es **publicar la página y poner el enlace en el
QR**:

1. En GitHub: **Settings → Pages → Source: Deploy from a branch**, elige esta
   rama y la carpeta `/ (root)`.
2. GitHub te da una URL tipo `https://vanayndergrays.github.io/lovepage/`.
3. Genera el QR con esa URL (cualquier generador gratuito sirve) e imprímelo
   para el regalo.

Consejo: prueba primero el enlace en tu propio teléfono, con datos móviles.
