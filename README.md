# Tabler Dashboard Template

Plantilla estática de tablero basada en Tabler, lista para usar y lista para subir a GitHub.

## Descripción

Este proyecto es una versión ya compilada de un dashboard UI moderno y responsivo construido con Tabler. Incluye múltiples páginas de ejemplo, componentes de interfaz y estilos / scripts precompilados en la carpeta `dist`.

## Características principales

- Dashboard responsive y listo para producción
- Varias páginas de ejemplo incluidas: `index`, `auth`, `perfil`, `invoice`, `settings`, `pricing`, `tables`, `charts`, `maps`, `cards`, y más
- Múltiples estilos de layout: `layout-boxed`, `layout-fluid`, `layout-horizontal`, `layout-vertical`, `layout-combo`, `layout-condensed`, etc.
- Componentes de UI: botones, tarjetas, formularios, tablas, modales, alertas, badges, pestañas, listas, navegación, dropdowns, carrusel y más
- Soporte de temas claro/oscuro mediante query param `?theme=dark` / `?theme=light`
- Activos estáticos listos en `dist/` y `static/`

## Estructura del proyecto

- `index.html` - página de inicio del dashboard
- `docs/` - redirecciona a la documentación oficial de Tabler
- `dist/` - CSS, JS y recursos compilados para producción
- `static/` - imágenes, iconos y assets usados por la plantilla
- Varios archivos HTML de ejemplo para componentes y páginas internas

## Requisitos

- Navegador moderno actualizado
- No requiere servidor backend para funcionar
- Para mejor experiencia local, se recomienda servirlo mediante un servidor HTTP simple

## Uso

### Abrir localmente

1. Copia todo el contenido del directorio al servidor o carpeta de tu sitio.
2. Abre `index.html` en el navegador.

> Nota: `index.html` utiliza un import de fuente externa (`https://rsms.me/inter/inter.css`). Si necesitas trabajo completamente offline, reemplaza esta importación con una fuente local.

### Servidor local recomendado

Desde la carpeta raíz del proyecto, usa uno de los siguientes comandos:

- Python 3:
  ```bash
  python -m http.server 8000
  ```
- Node.js (http-server):
  ```bash
  npx http-server . -p 8000
  ```

Luego abre `http://localhost:8000`.

## Páginas incluidas

Algunas de las páginas más relevantes incluidas en este proyecto:

- `index.html`
- `layout-combo.html`, `layout-boxed.html`, `layout-fluid.html`, `layout-horizontal.html`, `layout-vertical.html`, `layout-rtl.html`
- `sign-in.html`, `sign-up.html`, `forgot-password.html`, `auth-lock.html`
- `profile.html`, `settings.html`, `settings-plan.html`, `invoice.html`, `pricing.html`
- `tables.html`, `datatables.html`, `datagrid.html`
- `charts.html`, `maps.html`, `maps-vector.html`, `map-fullsize.html`
- `cards.html`, `cards-masonry.html`, `tabs.html`, `accordion.html`, `alerts.html`, `modals.html`
- `email.html`, `chat.html`, `job-listing.html`, `search-results.html`, `empty.html`, `error-404.html`, `error-500.html`

## Componentes y recursos

### Archivos CSS principales

- `dist/css/tabler.min.css`
- `dist/css/tabler-vendors.min.css`
- `dist/css/tabler-flags.min.css`
- `dist/css/tabler-payments.min.css`
- `dist/css/demo.min.css`

### Archivos JS principales

- `dist/js/demo-theme.min.js`

### Activos estáticos

- `static/avatars/`
- `static/brands/`
- `static/browsers/`
- `static/components/`
- `static/crypto-currencies/`
- `static/emails/`
- `static/illustrations/`
- `static/jobs/`
- `static/photos/`
- `static/products/`
- `static/projects/`
- `static/tracks/`

### Iconos

- Los iconos se incluyen inline en los archivos HTML con la librería Tabler Icons.

## Despliegue

Puedes desplegar esta plantilla en cualquier entorno estático local o en tu propio servidor. No es necesario usar GitHub Pages.

Opciones de despliegue:

- Local: abre `index.html` directamente en el navegador.
- Servidor propio: copia los archivos al directorio público de tu servidor web (Apache, Nginx, Caddy, etc.).
- Servidor HTTP simple: ejecuta un servidor local con Python, Node.js u otra herramienta ligera.

Ejemplo con Python 3:

```bash
python -m http.server 8000
```

Ejemplo con Node.js (`http-server`):

```bash
npx http-server . -p 8000
```

Luego abre `http://localhost:8000`.

> Este proyecto está pensado para uso local o en servidores propios, y funciona como un sitio estático completo.

## Personalización

- Modifica las páginas HTML para cambiar contenido, menús y widgets.
- Actualiza o reemplaza archivos CSS/JS en `dist/` para cambiar estilos y comportamiento.
- Agrega nuevas páginas o componentes siguiendo la estructura de las páginas de ejemplo.

## Notas importantes

- Proyecto orientado a sitios estáticos y demostraciones de UI.
- No incluye un flujo de compilación/desarrollo (`package.json` o `npm install`) en esta versión build.
- La plantilla se basa en `Tabler` y usa licencia MIT según los comentarios incluidos en `index.html`.

## Apoya el desarrollo del proyecto

Quiero invitarte a apoyar mi trabajo con un yapeo voluntario para que pueda seguir creando plantillas libres y open source.

- Puedes usar un código QR con tu enlace de Yape o cualquier otra billetera digital.
- Si decides apoyar este proyecto, tu aporte ayudará a mantener el desarrollo y permitir la creación de más recursos gratuitos.

<img src="https://placecomp.com/assets/img/codigoqr.jpg" width="250" alt="Código QR de donación">

> ¡Gracias de antemano a quienes deseen apoyar con un yapeo voluntario! Tu ayuda es muy valiosa para seguir desarrollando proyectos libres.

## Créditos

- `Tabler.io` — dashboard template open source
- `codecalm.net` / `Paweł Kuna`

---

> `README.md` preparado para GitHub: describe la plantilla, uso, recursos, páginas y despliegue.
