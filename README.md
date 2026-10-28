# Los Dos Faros · Club de Billar y Bar

Branding, página web, carta digital y material de mesa del Club de Billar Los Dos Faros (Guayabal, Medellín).

## Estructura

| Carpeta | Contenido | Estado |
|---|---|---|
| raíz | Página web de una sola página (`index.html`) con sus fotos en `img/`. | v1 para revisión |
| `carta/` | Carta digital para celular (`index.html`), pensada para abrirse desde el QR de las mesas. Tarifa vigente según la hora de Bogotá. | Aprobada (27-oct-2026) |
| `marca/logo/svg/` | Logo aprobado (Propuesta C · "Dos luces sobre el paño") en SVG: principal a color, una tinta, ícono de perfil e ícono pequeño. | Aprobado (27-oct-2026) |
| `marca/logo/` | Tablero de diseño con el logo original y las tres propuestas (A, B, C). Archivos `.dc.html` del editor de diseño de Claude; `assets/logo-original.png` es el logo anterior. | Referencia |
| `qr/` | Cartel A5 de mesa "Escanea y mira la carta" (`Main.dc.html`) y el código QR en `assets/qr-carta.svg`. | Prueba |
| `docs/` | Decisiones de marca, catálogo de productos y precios, fotos pendientes y contexto del negocio. | Vigente |

## Ver localmente

`index.html` y `carta/index.html` se abren directo en el navegador. Las fuentes (Big Shoulders Display y Archivo) se cargan desde Google Fonts, así que se necesita internet para verlas bien.

Los archivos `.dc.html` de `marca/logo/` y `qr/` son tableros del editor de diseño de Claude y no se ven bien fuera de él; para uso real están los SVG de `marca/logo/svg/`.

## Paleta y tipografía

- Hueso `#F4EFE6` (fondo) · Rojo faro `#E0313F` · Ámbar faro `#F5B83D` · Verde paño `#1F7A4D` · Tinta `#0D1B24` (solo trazos y texto)
- Big Shoulders Display 800 para nombre y títulos; Archivo 400/600 para textos y precios.

## Publicación

Publicado con GitHub Pages: web en https://sebaxtian1011.github.io/BillarLosDosFaros/ y carta en https://sebaxtian1011.github.io/BillarLosDosFaros/carta/. A futuro se recomienda un dominio propio (por ejemplo losdosfaros.co) para que el QR impreso no dependa de GitHub.

## Pendiente

- Fotos reales que faltan (ver `docs/fotos-pendientes.md`).
- Dominio propio y publicación de web y carta; regenerar el QR apuntando al dominio.
- Exportar logo en PNG y manual de marca breve.
- Actualización del archivo de inventario (control mensual).
