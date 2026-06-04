# 🍼 Si Mamá!!! Bolivia — Tienda Web

Sitio web completo para la tienda de extractores de leche materna **Si Mamá!!! Bolivia**.

## 📁 Archivos

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Tienda pública (clientes) |
| `admin.html` | Panel de administración |

## 🚀 Cómo usar localmente

1. Descarga ambos archivos en la **misma carpeta**
2. Abre `index.html` en tu navegador (doble clic o arrastrar)
3. Para el admin abre `admin.html`

> ⚠️ Los datos se guardan en `localStorage` del navegador. No necesitas servidor ni base de datos.

## 🔐 Credenciales de Admin

| Campo | Valor |
|-------|-------|
| Usuario | `admin` |
| Contraseña | `mamita2026` |

## 📱 Cambiar número de WhatsApp del admin

### En `index.html`
Busca esta línea al inicio del `<script>`:
```js
const ADMIN_WA = '59162303015';
```
Cámbiala por tu número real (sin `+`, sin espacios, con código de país).

### En `admin.html`
(El admin no envía WA, solo registra pedidos internamente.)

## ✨ Funcionalidades

### Tienda (`index.html`)
- 🏠 Página de Inicio con productos destacados
- 🛒 **Carrito de compras** con cajón lateral deslizante
- 🛍️ Página de Productos con pestañas por categoría:
  - ✋ Manuales
  - 🔓 Manos Libres
  - ⚡ Doble Extracción
  - 📱 Portátiles
  - 🎀 Accesorios
- 💖 Página Sobre Nosotros con galería de fotos y videos de ferias
- ▶️ Página Cómo Usar con videos instructivos
- 📍 Página Ubicación con contacto
- Botón "Al carrito" + botón "Pedir" por WhatsApp individual
- Pedido de carrito completo por WhatsApp
- Botón flotante de WhatsApp para contacto general

### Admin (`admin.html`)
- 📊 Dashboard con estadísticas
- 📦 Gestión de productos (agregar, editar, eliminar, fotos)
- 🛍️ Lista de pedidos con cambio de estado
- 🖼️ Gestión de Fotos & Videos:
  - Fotos de ferias (aparecen en "Sobre Nosotros")
  - Videos de ferias (YouTube o URL directa)
  - Videos de uso (aparecen en "Cómo Usar")

## 🌐 Subir a GitHub Pages

1. Crea un repositorio en GitHub
2. Sube `index.html` y `admin.html`
3. Ve a **Settings → Pages → Source: main branch**
4. Tu sitio estará en `https://tuusuario.github.io/nombre-repo/`

## 💡 Tips para imágenes de productos

- Sube fotos a [Imgur.com](https://imgur.com) (gratis, URL directa)
- O usa Google Drive: clic derecho → Obtener enlace → Acceso para cualquiera → copiar link
  - Cambia el link de Drive de: `drive.google.com/file/d/ID/view` 
  - A: `drive.google.com/uc?export=view&id=ID`

---
Hecho con 💕 para las mamás bolivianas · Si Mamá!!! Bolivia · 2026
