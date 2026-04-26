# Bellísima Estética Avanzada

Web oficial del centro de estética Bellísima, Arganda del Rey.

## Estructura del proyecto

```
bellisima/
├── index.html        ← página principal
├── sitemap.xml       ← para Google
├── robots.txt        ← para buscadores
└── img/              ← todas las fotos
    ├── exterior.jpg
    ├── sala1.jpg
    ├── sala2.jpg
    ├── recepcion.jpg
    ├── esquina.jpg
    ├── sala3.jpg
    ├── esteticista.jpg
    ├── ad_piernas.jpg
    ├── ad_abdomen1.jpg
    ├── ad_abdomen2.jpg
    ├── ad_pestanas.jpg
    ├── ad_cejas.jpg
    └── logo.jpg

## Publicar en GitHub Pages

1. Crea un repositorio en github.com/new
2. Sube TODOS los archivos (index.html + img/ + sitemap.xml + robots.txt)
3. Ve a Settings → Pages → Branch: main → / (root) → Save
4. Tu web estará en: https://TU-USUARIO.github.io/NOMBRE-REPO/

## Dar de alta en Google Search Console

1. Ve a search.google.com/search-console
2. Añade tu dominio o URL de GitHub Pages
3. Verifica la propiedad (opción HTML tag: pega el código en el <head> del index.html)
4. Envía el sitemap: https://TU-USUARIO.github.io/NOMBRE-REPO/sitemap.xml

## Cambiar el dominio (si tienes bellisimaestetica.es)

1. En tu proveedor de dominio, añade un CNAME apuntando a TU-USUARIO.github.io
2. En GitHub Pages → Custom domain → escribe bellisimaestetica.es
3. Actualiza las URLs del sitemap.xml y robots.txt
