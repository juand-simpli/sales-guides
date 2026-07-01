# SimpliRoute — Sales Enablement

Repositorio central de **guías internas de conocimiento / ventas** de SimpliRoute.
Cada guía es una página HTML autocontenida (sin dependencias externas) con la identidad visual oficial.

🔗 **Landing page:** una vez publicado con GitHub Pages, estará en
`https://<TU-USUARIO>.github.io/<NOMBRE-DEL-REPO>/`

## Contenido

| Archivo | Guía |
|---|---|
| `index.html` | Landing page / índice de guías |
| `guia_pago_a_proveedores.html` | Módulo Pago a Proveedores |
| `guia_transporte_pasajeros.html` | Producto Transporte de Pasajeros |
| `guia_ciberseguridad.html` | Ciberseguridad para preventa (ISO 27001, GCP, SSO, cifrado, incidentes) |

## Cómo publicar con GitHub Pages

1. Sube todos los archivos a un repositorio **público** (en la raíz).
2. En el repo: **Settings → Pages**.
3. En **Build and deployment → Source**, elige **Deploy from a branch**.
4. Branch: **main**, carpeta: **/ (root)**. Guarda.
5. Espera 1–2 minutos. El sitio quedará en `https://<TU-USUARIO>.github.io/<NOMBRE-DEL-REPO>/`.

## Cómo agregar una guía nueva

1. Sube el nuevo archivo `.html` al repo (nombre en minúsculas, sin tildes ni espacios).
2. En `index.html`, duplica un bloque `<a class="guide-card"> ... </a>` y ajusta icono, título, `<span class="badge">` y `href`.

---
**Uso interno y confidencial.** Si el repositorio es público, este material será visible en internet.
