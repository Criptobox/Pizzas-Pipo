# 🍕 Pizzas Pipo - Catálogo Digital

Catálogo web responsive para Pizzas Pipo con diseño dark premium, carrito de compras y pedidos por WhatsApp.

## ✨ Características

- 🎨 **Diseño dark premium** con glass-morphism y animaciones
- 🛒 **Carrito de compras** con persistencia en localStorage
- 📱 **Responsive** - funciona perfecto en móvil y desktop
- 🔍 **Buscador** de productos en tiempo real
- 🏷️ **Filtros** por categoría (Pizzas, Bebidas, Extras)
- 💬 **Pedido directo por WhatsApp** con detalles del carrito
- ⚡ **Single-file** - solo necesitas index.html, sin build

## 🚀 Despliegue en GitHub Pages

1. Crea un nuevo repositorio en GitHub (ej: `pizzas-pipo`)
2. Sube los archivos:
   ```bash
   git init
   git add .
   git commit -m "feat: catálogo Pizzas Pipo v3"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/pizzas-pipo.git
   git push -u origin main
   ```
3. Ve a **Settings → Pages** en tu repo
4. En **Source**, selecciona la rama `main` y carpeta `/root`
5. Guarda — tu sitio estará en: `https://TU_USUARIO.github.io/pizzas-pipo/`

## 🛠️ Personalización

Edita `index.html` para cambiar:
- **Productos**: array `products[]` en el `<script>`
- **Teléfono WhatsApp**: busca `5312345678` y reemplaza
- **Dirección y horarios**: sección "Información del local"
- **Colores**: variables CSS en `<style>`

## 📁 Estructura

- `index.html` — catálogo completo (single-file)
- `README.md` — este archivo
- `.gitignore`
- `LICENSE` — MIT

## 📞 Contacto

Pizzas Pipo · 🍕 Sabor italiano artesanal
