Avance de Proyecto - Rincón Parrillero
Versión: 1.0
Grupo: 4

Integrantes:

- MEZA ALCEDO JHAIR CHRISTOPHER
- MEDINA LIZANA JOEL FERNANDO
- QUILLO INGA CARLOS DANIEL


1. Descripción del proyecto

El presente proyecto consiste en el desarrollo de una página web estática tipo landing page para el restaurante “Rincón Parrillero”, utilizando el framework Bootstrap 5.

La página muestra información general del restaurante, una sección de platos mediante tarjetas (cards), horarios de atención, un formulario de reservas y un pie de página (footer) con información adicional. Todo el diseño está adaptado a diferentes tamaños de pantalla, cumpliendo con criterios de diseño responsive.


2. Instrucciones de ejecución

Para visualizar el proyecto:

1. Descargar o descomprimir la carpeta del proyecto.
2. Abrir la carpeta en el explorador de archivos.
3. Ejecutar el archivo “index.html” con cualquier navegador web (Chrome, Edge, etc.).

No se requiere instalación adicional.


3. CDN utilizado

Se utilizó Bootstrap versión 5.3.3 mediante CDN:

CSS:
https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css

JavaScript:
https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js


4. Componentes de Bootstrap implementados

✅ Navbar responsive con menú colapsable (toggler)
✅ Sistema de grillas (container, row, col-*)
✅ Cards para la presentación de platos (mínimo 4)
✅ Tabla estilizada (table, table-striped, table-hover)
✅ Imágenes responsivas (img-fluid)
✅ Formulario de reserva con múltiples campos
✅ Modales para mostrar información detallada
✅ Uso de utilities (espaciado, alineación, sombras, bordes, etc.)


5. Diseño responsive

El sitio se adapta correctamente a diferentes resoluciones:

* Dispositivos móviles: el menú se colapsa y los elementos se organizan en una sola columna.
* Tablets: distribución intermedia.
* Escritorio: visualización completa con múltiples columnas.

Se emplearon clases como:
col-12, col-sm-6, col-md-3, navbar-expand-lg, img-fluid, entre otras.


6. Estilos personalizados (CSS)

Se implementó un archivo externo “styles.css” para complementar Bootstrap, donde se definieron:

* Tipografía general del sitio
* Colores de títulos acordes a la temática del restaurante
* Efecto hover en tarjetas
* Tamaño uniforme de cards e imágenes
* Uso de flexbox para alineación interna
* Estilos personalizados para el footer


7. Funcionalidad con JavaScript

Se creó un archivo “script.js” con una funcionalidad básica para el formulario:

* Se captura el evento de envío (submit)
* Se evita la recarga de la página con preventDefault()
* Se muestra un mensaje de confirmación mediante alert()


8. Estructura del proyecto

proyecto/
│
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── assets/
│   └── imágenes del proyecto
├── capturas/
│   ├── mobile.png
│   └── desktop.png
└── README.txt


9. Conclusión

El proyecto demuestra la implementación de una página web básica utilizando Bootstrap, integrando componentes visuales, diseño responsive, estilos personalizados y una funcionalidad básica con JavaScript, logrando una interfaz clara, ordenada y funcional.
