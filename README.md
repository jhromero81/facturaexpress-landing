# FacturaExpress — Landing page (evidencia GA10-220501097-AA6-EV01)

Plantilla web gratuita usada como producto de prueba para el despliegue en producción
del Resultado de aprendizaje **220501097-02 — Desplegar el software de acuerdo con la
arquitectura y las políticas establecidas** (SENA, Análisis y Desarrollo de Software).

## Origen de la plantilla

| Elemento | Detalle |
|---|---|
| Nombre | Landed |
| Autor | AJ (ajlkn) — HTML5 UP |
| Sitio | https://html5up.net/landed |
| Descarga | https://html5up.net/landed/download |
| Licencia | Creative Commons Attribution 3.0 (CCA 3.0), uso personal y comercial |
| Tecnología | HTML5, CSS3 (Sass incluido en el paquete original), jQuery, Font Awesome |
| Selección | Tomada del listado de plantillas HTML gratuitas de dev.to (Pacilio, 2020) y de la galería de HTML5 UP |

## Ajustes realizados sobre la plantilla original

1. **Traducción completa al español**: títulos, navegación, textos del banner, secciones
   de producto, formulario y pie de página (el paquete original está en inglés).
2. **Identidad del producto**: la plantilla se personalizó para FacturaExpress, el proyecto
   formativo, en lugar del texto de relleno en latín (*lorem ipsum*).
3. **Idioma del documento**: `lang="es"` y `<meta charset="utf-8">`.
4. **SEO y metadatos**: `title`, `description`, `author`, `og:title`, `og:description`,
   `og:type`.
5. **Navegación**: menú y anclas apuntando a las secciones de la página; se eliminaron las
   páginas de demostración del paquete (`elements.html`, `left-sidebar.html`,
   `right-sidebar.html`, `no-sidebar.html`) para publicar un sitio de una sola página.
6. **Accesibilidad**: atributo `alt` descriptivo en todas las imágenes y `<span class="label">`
   en los iconos sociales (el original dejaba varios `alt` vacíos).
7. **Enlaces reales**: el icono de GitHub apunta al perfil del autor del despliegue.
8. **Pie de página**: aviso de copyright y atribución de la licencia de la plantilla,
   obligatoria según CCA 3.0.
9. **Fuentes del paquete**: se eliminó la carpeta `assets/sass` (fuentes de compilación, no
   necesarias en producción) para reducir el peso publicado.

## Estructura del sitio

```
index.html                 Página única en español
assets/css/                Hojas de estilo compiladas
assets/js/                 Dependencias (jQuery, scrolly, dropotron, scrollex, util, main)
assets/webfonts/           Tipografías e iconos Font Awesome
images/                    Imágenes de demostración (Unsplash, dominio público)
LICENCIA-PLANTILLA.txt     Licencia original CCA 3.0 de HTML5 UP
```

## Despliegue

- **Hosting**: GitHub Pages (plan gratuito), publicación desde la rama `main`, carpeta raíz.
- **Dominio**: subdominio gratuito configurado con registros DNS hacia GitHub Pages.
- **HTTPS**: certificado TLS gestionado automáticamente por GitHub Pages.

Las capturas del paso a paso y la justificación de cada decisión están en el informe de la
evidencia (`GA10-220501097-AA6-EV01_JhonHenryRomero.docx`).

## Créditos

- Diseño base: Landed by HTML5 UP — https://html5up.net — licencia CCA 3.0.
- Imágenes de demostración: Unsplash (dominio público).
- Iconos: Font Awesome.
