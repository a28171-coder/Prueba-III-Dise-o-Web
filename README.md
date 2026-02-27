Salón del Automóvil Aragón 2026 – README
Descripción del proyecto
Página web informativa de una sola página (landing page) para el Salón del Automóvil Aragón 2026 en Zaragoza.
El objetivo es presentar el evento de forma clara y atractiva, mostrando la información esencial: qué es, cuándo se celebra, dónde se realiza y cómo contactar.

Tecnologías utilizadas
HTML5 para la estructura de la página.

CSS3 mediante:

Framework Bootstrap 5.3.3 cargado por CDN.

Hoja de estilos personalizada css/custom.css para ajustes propios.

JavaScript incluido dentro del bundle de Bootstrap (para componentes interactivos si se añaden más adelante).

Google Maps Embed para mostrar la ubicación del recinto ferial.

Estructura principal del archivo
El archivo principal es index.html y contiene:

Cabecera (<head>)

Declaración de tipo de documento y lengua: <!DOCTYPE html> y lang="es".

Metadatos de codificación (UTF-8) y diseño responsive (viewport).

Título de la página: Salón del Automóvil Aragón 2026 - Zaragoza.

Enlace al CSS de Bootstrap via CDN.

Enlace a la hoja de estilos personalizada: css/custom.css.

Sección Hero

Fondo primario (bg-primary), texto en blanco y centrado.

Logo del evento (img/logo.png).

Título grande con display-4 y texto destacado.

Breve descripción del evento.

Botón que enlaza a la sección de información esencial (#info).

Sección de Información Esencial (#info)

Contenedor Bootstrap (.container) con una fila (.row) y tres columnas (.col-md-4):

¿Qué es?: Descripción de la feria automovilística.

¿Cuándo?: Fechas y horario del evento.

¿Dónde?: Dirección del Recinto Ferial de Zaragoza y una imagen (img/pabellon.jpg) con clases img-fluid y rounded.

Sección Mapa y Contacto

Fondo claro (bg-light) con padding vertical.

Nueva fila con dos columnas:

Columna izquierda (.col-md-8): Título “Ubicación” e iframe de Google Maps a pantalla completa en ancho.

Columna derecha (.col-md-4): Información de contacto (email del ayuntamiento, teléfono) y botón para enviar consulta por correo (mailto:info@salonautaragon.es).

Scripts

Inclusión del bundle de Bootstrap 5.3.3 vía CDN justo antes del cierre de <body>.

Estructura de carpetas recomendada
text
proyecto-salon-auto/
│
├─ index.html
├─ css/
│  └─ custom.css
└─ img/
   ├─ logo.png
   └─ pabellon.jpg
Cómo ejecutar el proyecto
Crea la estructura de carpetas anterior.

Guarda el contenido proporcionado en un archivo index.html en la raíz del proyecto.

Guarda las imágenes logo.png y pabellon.jpg dentro de la carpeta img/.

(Opcional) Crea el archivo css/custom.css para añadir estilos personalizados.

Abre index.html en cualquier navegador moderno (Chrome, Firefox, Edge, etc.).

No es necesario ningún servidor web específico; basta con abrir el archivo localmente para ver la página.

Personalización básica
Cambiar colores: puedes sobrescribir clases de Bootstrap o añadir clases propias en css/custom.css.

Modificar textos: edita directamente el contenido de los <h1>, <h2>, <h3> y <p> en index.html.

Actualizar fechas, horarios o dirección: ajusta los textos de la sección “Info Esencial”.

Cambiar el mapa: modifica la URL del <iframe> de Google Maps con la ubicación deseada.
