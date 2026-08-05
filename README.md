# Pizzas Pipo - Catálogo Digital

Catálogo digital de pizzas con carrito, panel admin, ofertas, favoritos, modo claro/oscuro y PWA. Listo para GitHub Pages.

## Características v4

- **Panel Admin** (tocar 3 veces el logo, contraseña: `pipo123`):
  - Editar productos (nombre, descripción, precio, fotos, ingredientes, tamaños, extras)
  - Crear ofertas y combos con countdown timer
  - Editar datos del local (WhatsApp, dirección, horarios, Instagram, Facebook)
  - Exportar/importar backup JSON
  - Restablecer datos

- **Personalización de productos**:
  - Tamaños (Individual/Mediana/Familiar) con precios
  - Extras (extra queso, borde con queso, etc.)
  - Notas del producto (sin cebolla, bien cocida...)

- **Sistema de ofertas y combos**:
  - Badges de ahorro
  - Countdown timers (termina hoy a medianoche)
  - Combos con múltiples productos
  - Cupones de descuento

- **Favoritos**: botón ♥ en cada producto, filtros por favoritos

- **Modo oscuro/claro/automático** con persistencia

- **PWA**: instalable como app, manifest + service worker

- **Historial de pedidos**: repetir último pedido o cualquier pedido anterior

- **Estado real de apertura**: detecta automáticamente si está abierto según horario

- **SEO**: meta tags Open Graph, Twitter Cards, theme-color

- **Pedidos por WhatsApp** con detalles completos (cantidad, extras, notas, total)

## Despliegue en GitHub Pages

1. Crea un repositorio nuevo en GitHub (ej: `pizzas-pipo`)
2. Sube los archivos:
   ```bash
   git init
   git add .
   git commit -m "Catálogo Pizzas Pipo v4"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/pizzas-pipo.git
   git push -u origin main
   ```
3. Ve a **Settings → Pages → Source: main branch**
4. Tu catálogo estará en: `https://TU_USUARIO.github.io/pizzas-pipo/`

## Personalización

- **Contraseña admin**: cambia `pipo123` en la función `adminLogin()`
- **Productos**: desde el panel admin (3 toques en el logo)
- **Colores**: variables CSS `--accent`, `--accent-2` en `:root`

## Tecnología

- HTML + Tailwind CSS (CDN) + Font Awesome 6.4.0
- Google Fonts (Inter + Playfair Display)
- SVG inline para imágenes (sin dependencias externas)
- localStorage para persistencia
- Service Worker para PWA

## Licencia

MIT
