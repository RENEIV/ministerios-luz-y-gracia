# Ministerios Luz y Gracia / Light & Grace Ministries

Starter bilingüe, mobile-first y preparado para GitHub + Netlify.

## Archivos principales

- `index.html`: página principal en español.
- `en/index.html`: página principal en inglés.
- `assets/css/styles.css`: diseño global.
- `assets/js/main.js`: menú móvil, año y PWA.
- `netlify.toml`: publicación, cabeceras de seguridad y redirecciones.
- `manifest.webmanifest` y `service-worker.js`: instalación básica como PWA.
- Formularios Netlify: `prayer-request-es`, `prayer-request-en`, `contacto-es`, `contact-en`.

## Antes de publicar

Busque y reemplace:

- `TU-DOMINIO.org`
- `INFO@TU-DOMINIO.org`
- `(000) 000-0000`
- Dirección pública
- Nombre legal, EIN y declaración 501(c)(3)
- Texto de la política de privacidad
- Código oficial de PayPal Donate

## Publicación en GitHub

1. Cree un repositorio nuevo.
2. Suba **el contenido de esta carpeta**, manteniendo `index.html` en la raíz.
3. Haga commit en la rama `main`.

## Conectar a Netlify

1. En Netlify: **Add new project → Import an existing project**.
2. Seleccione GitHub y este repositorio.
3. Build command: déjelo vacío.
4. Publish directory: `.`
5. Publique.
6. En Netlify abra **Forms** y active **Form detection**.
7. Haga un redeploy.
8. Envíe una petición de prueba y compruebe que aparece en Forms.
9. Configure notificaciones de formularios solamente a correos autorizados.

## PayPal

Genere un botón o integración Donate desde la cuenta oficial de PayPal de la organización. Pegue el código dentro de:

`<div id="paypal-donate-button-container">`

No suba claves secretas al repositorio.

## Seguridad y privacidad

Netlify Forms es una base inicial para recibir solicitudes. No es un sistema de expedientes pastorales. No agregue notas confidenciales en GitHub ni en HTML público. Para flujos sensibles, roles, auditoría y retención formal, agregue después una base de datos y autenticación administrativa.

La política incluida es una plantilla operativa, no asesoramiento legal.
