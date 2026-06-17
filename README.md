# SimpliRoute — Sales Enablement

Repositorio central de **guías rápidas de ventas** de SimpliRoute para el equipo comercial.
Cada guía es una página HTML autocontenida (sin dependencias externas) con la identidad visual oficial.

🔗 **Landing page:** una vez publicado con GitHub Pages, estará en
`https://<TU-USUARIO>.github.io/<NOMBRE-DEL-REPO>/`

## Contenido

| Archivo | Guía |
|---|---|
| `index.html` | Landing page / índice de guías |
| `guia_pago_a_proveedores.html` | Módulo Pago a Proveedores |
| `guia_transporte_pasajeros.html` | Producto Transporte de Pasajeros |

## Cómo publicar con GitHub Pages

1. Sube todos los archivos a un repositorio **público**.
2. En el repo: **Settings → Pages**.
3. En **Build and deployment → Source**, elige **Deploy from a branch**.
4. Branch: **main**, carpeta: **/ (root)**. Guarda.
5. Espera 1–2 minutos. Tu sitio quedará en `https://<TU-USUARIO>.github.io/<NOMBRE-DEL-REPO>/`.

## Cómo agregar una guía nueva

1. Sube el nuevo archivo `.html` al repo.
2. En `index.html`, duplica un bloque `<a class="guide-card"> ... </a>` y ajústalo (icono, título, descripción y `href`).

---
**Uso interno y confidencial.** Si el repositorio es público, este material será visible en internet.
