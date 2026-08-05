# 🍕 Pizzas Pipo - Catálogo Digital

Catálogo web responsive con panel de administración integrado, carrito de compras y pedidos por WhatsApp.

## ✨ Características

### 🎨 Diseño
- Tema dark premium con glass-morphism y gradientes
- Animaciones suaves (fade-up, shimmer, float, pulse)
- Totalmente responsive (móvil, tablet, desktop)
- Tipografía Playfair Display + Inter

### 🛒 Carrito y pedidos
- Carrito lateral con persistencia (localStorage)
- Personalización: tamaños, extras y notas por producto
- Pedido directo por WhatsApp con detalle completo
- Selector de cantidad

### 🔐 Panel Admin (tocar logo 3 veces)
- **Productos**: crear, editar, eliminar, subir fotos
- **Local**: nombre, dirección, teléfono, horarios, redes sociales
- **Datos**: exportar/importar backup JSON, restablecer
- Contraseña por defecto: `pipo123`

### ⏰ Horarios inteligentes
- Status real: "Abierto ahora" o "Cerrado"
- Se actualiza automáticamente cada minuto

## 🚀 Despliegue en GitHub Pages

1. Crea un repositorio en GitHub (ej: `pizzas-pipo`)
2. Sube los archivos:
   ```bash
   git init
   git add .
   git commit -m "feat: catálogo Pizzas Pipo v3 con admin"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/pizzas-pipo.git
   git push -u origin main
   ```
3. Ve a **Settings → Pages**
4. Source: rama `main`, carpeta `/root`
5. Tu sitio: `https://TU_USUARIO.github.io/pizzas-pipo/`

## 🔐 Cómo usar el panel admin

1. Toca el logo "Pizzas Pipo" **3 veces** en el header
2. Ingresa la contraseña: `pipo123`
3. Gestiona productos, datos del local y backups

## 🛠️ Personalización

Toda la gestión se hace desde el panel admin (sin tocar código):
- **Productos**: nombre, descripción, precio, categoría, tag, ingredientes, foto
- **Local**: marca, hero, WhatsApp, dirección, horarios, Instagram, Facebook
- **Datos**: exportar/importar para migrar entre dispositivos

## 📁 Estructura

- `index.html` — catálogo completo (single-file)
- `README.md` — este archivo
- `.gitignore`
- `LICENSE` — MIT

## 📞 Contacto

Pizzas Pipo · 🍕 Sabor italiano artesanal
