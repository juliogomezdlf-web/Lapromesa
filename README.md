# 🛒 La Promesa - Sistema de Gestión de Tienda

Una **aplicación web moderna y completa** para gestionar una abarrotera o tienda pequeña. Diseñada para ser intuitiva, rápida y sin necesidad de servidor backend.

## ✨ Características

### 🏪 **Tienda Online**
- Catálogo de **104 productos** precargados (bebidas, alimentos, abarrotes, etc.)
- 11 categorías: Refrescos, La Costeña, Abarrotes, Botanas, Dulcería, Panadería, Lácteos, Limpieza, Higiene y Medicamentos
- 🔍 **Búsqueda en tiempo real**
- 📱 **Diseño responsive** - funciona perfecto en celular, tablet y PC
- Carrito de compras con cálculo automático de totales

### 📋 **Sistema de Pedidos**
- Los clientes pueden hacer pedidos y dejar notas especiales
- Historial de pedidos con búsqueda por nombre o teléfono
- Estados de pedido: ⏳ Pendiente → ✅ Listo → 📦 Entregado

### 🔐 **Área de Administrador**
- Panel protegido por contraseña
- **Gestión de inventario**: Agregar, editar y eliminar productos
- **Panel de pedidos**: Ver y cambiar estado de órdenes de clientes
- Estadísticas en tiempo real: Total de productos, pedidos pendientes, stock bajo
- Alertas visuales de productos con stock bajo o agotados

### 💾 **Almacenamiento Local**
- Todos los datos se guardan en el navegador del cliente (localStorage)
- **Sin servidor necesario** - perfecta para pequeños negocios
- Los datos persisten entre sesiones

### 🎨 **Diseño Hermoso**
- Interfaz moderna con colores cálidos (rojo, naranja, beige)
- Tipografía elegante con Playfair Display y Nunito
- Emojis para mejor experiencia visual
- Animaciones suaves y transiciones

## 🚀 Cómo Usar

### Opción 1: En Línea (Recomendado)
1. Abre: [https://juliogomezdlf-web.github.io/Lapromesa/](https://juliogomezdlf-web.github.io/Lapromesa/)
2. ¡Listo! La aplicación está en vivo

### Opción 2: Localmente
1. Descarga el archivo `index.html`
2. Abre el archivo en cualquier navegador
3. No necesita conexión a internet

## 👥 Usuarios y Contraseñas

### Cliente
- Acceso público en la sección "🏪 Tienda"
- Puede ver productos, hacer pedidos y revisar su historial

### Admin/Dueño
1. Ve a la pestaña "🔐 Admin"
2. **Contraseña**: `Lapromesa2025` (modifica según tus necesidades)
3. Acceso a inventario y gestión de pedidos

## 🔧 Cómo Cambiar la Contraseña

1. Abre `index.html` en un editor de texto
2. Busca la línea: `const OWNER_HASH = "a665a45920422f9d417e4867efdc4fb8a04a1f3fff1fa07e998e86f7f7a27ae3";`
3. Usa un generador SHA-256 online (ej: [SHA256 Online](https://www.tools4noobs.com/online_tools/hash/)) para hashear tu nueva contraseña
4. Reemplaza el valor del hash

**O simplemente contacta para que lo hagas** 😊

## 📦 Editar Productos

En el panel Admin:

1. **Agregar**: Click en "+ Nuevo"
2. **Editar**: Click en ✏️ en el producto
3. **Eliminar**: Click en 🗑 en el producto
4. Puedes elegir ícono, precio, stock y categoría

## 🎯 Características Técnicas

- **Vanilla JavaScript** - Sin dependencias externas
- **100% Cliente** - No requiere servidor
- **localStorage** - Datos persistentes
- **SHA-256** - Autenticación segura
- **PWA-Ready** - Puede funcionar offline

## 📱 Compatibilidad

✅ Chrome, Firefox, Safari, Edge
✅ Android, iOS, Windows, macOS, Linux
✅ Funciona con o sin internet (datos guardados localmente)

## 🛠️ Personalización

Puedes modificar:

- **Nombre de tienda**: Cambia "La Promesa" en el `<title>` y el HTML
- **Ubicación**: "Villahermosa, Tab." en el header
- **Productos iniciales**: Edita el array `SEED_PRODUCTS`
- **Categorías**: Modifica el array `CATS`
- **Colores**: Busca `#C0392B` (rojo principal) en el CSS y reemplaza

## 🔄 Cómo Desplegar en GitHub Pages

Ya está listo para GitHub Pages! Solo asegúrate de que:

1. El repositorio es **público**
2. `index.html` está en la **raíz** del repositorio
3. Ve a **Settings → Pages** y selecciona **Source: main** (o tu rama)
4. Tu app estará en: `https://[tuusuario].github.io/Lapromesa/`

## 📝 Notas Importantes

- Los datos se guardan **solo en el navegador** del usuario
- Si el usuario limpia caché/historial, los datos se pierden
- Para un negocio real, considera migrar a una base de datos
- La contraseña admin es SHA-256 hasheada en el cliente

## 🤝 Contribuciones

¿Tienes ideas para mejorar La Promesa? ¡Las contribuciones son bienvenidas!

## 📄 Licencia

MIT - Úsala libremente para tu negocio

---

**Hecho con ❤️ para pequeños negocios de Tabasco** 🇲🇽

¿Preguntas o problemas? Abre un [Issue](https://github.com/juliogomezdlf-web/Lapromesa/issues)
