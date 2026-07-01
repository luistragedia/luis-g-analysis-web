# Luis G. Analysis Web

Web inicial del proyecto **Luis G. Analysis**.

**Lema:**  
La memoria falla. Los sistemas permanecen.

## Estado

Versión actual en desarrollo: **Web V1.1**.

La web funciona como portada pública del sistema y como punto de entrada a la futura biblioteca digital.

## Objetivo

Este repositorio contiene la versión web estática de la biblioteca Luis G. Analysis.

La web servirá como portada pública del sistema de conocimiento y, progresivamente, como índice navegable de manuales, guías, documentos, recursos y descargas digitales.

## Estructura

```text
luis-g-analysis-web/
├── index.html
├── favicon.png
├── README.md
├── .cpanel.yml
├── robots.txt
├── sitemap.xml
├── 404.html
├── assets/
│   ├── css/
│   ├── img/
│   └── js/
├── biblioteca/
│   └── index.html
├── downloads/
│   └── index.html
└── docs/
    └── guia-inicial-v0-1.html
```

## Páginas actuales

- `index.html`: landing principal.
- `biblioteca/index.html`: índice inicial de la biblioteca digital.
- `docs/guia-inicial-v0-1.html`: primera guía web del proyecto.
- `downloads/index.html`: centro de descargas preparado para futuros PDF, EPUB y listas de verificación.
- `404.html`: página de error personalizada.

## Archivos técnicos

- `robots.txt`: reglas básicas de rastreo.
- `sitemap.xml`: mapa inicial del sitio.
- `.cpanel.yml`: instrucciones de despliegue hacia cPanel.

## Despliegue

El despliegue está preparado para cPanel mediante `.cpanel.yml`.

Ruta configurada:

```text
/home/lstocks3/analisis.luisguacache.com/
```

Flujo operativo:

```text
1. Cambios en GitHub.
2. cPanel → Update from Remote.
3. cPanel → Deploy HEAD Commit.
4. Verificación en https://analisis.luisguacache.com
```

## Revisión previa al despliegue

Antes de fusionar una actualización a `main`, revisar:

```text
- Ortografía y acentuación.
- Enlaces internos.
- Visualización en móvil.
- Archivos incluidos en .cpanel.yml.
- Ausencia de datos privados o sensibles.
```

## Nota importante

No subir contraseñas, claves privadas, tokens, datos personales sensibles ni archivos internos no publicables.

Todo contenido público debe tener ortografía revisada, acentuación correcta y redacción cuidada.
