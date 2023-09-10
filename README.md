# 🛍️ Go-Ecommerce

## 📝 Descripción
Plataforma E-commerce construida sobre una arquitectura de microservicios utilizando Golang y Node.js. Este sistema permite una experiencia de compra integral, desde la navegación de productos hasta el pago, con una integración especial con WebPay. Ofrece flexibilidad, escalabilidad y resiliencia, garantizando una experiencia óptima para el usuario final.

## 🌟 Características Principales:

### 📦 Microservicio de Productos
Este microservicio gestiona todo lo relacionado con la presentación, búsqueda y categorización de productos dentro del E-commerce. Se encarga de mantener actualizada la base de datos de productos y proporciona funciones de filtrado y búsqueda.

#### Funcionalidades Principales
- 🔍 Búsqueda: Permite a los usuarios buscar productos específicos dentro del catálogo.
- 🏷️ Filtrado: Filtra productos por categoría, precio, marca y otros criterios.
🖼️ Presentación de Producto: Muestra detalles de un producto específico, incluyendo imágenes, descripción, precio y más.

### 🛒 Microservicio de Carrito
Responsable de gestionar el carrito de compras de los usuarios. Permite agregar, modificar y eliminar productos del carrito y convertir el carrito en un pedido una vez que se procede al pago.

#### Funcionalidades Principales
➕ Agregar Productos: Añade productos al carrito de un usuario.
➖ Eliminar Productos: Retira productos del carrito.
🔄 Modificar Cantidad: Cambia la cantidad de un producto en el carrito.
💼 Convertir a Pedido: Convierte el carrito en un pedido en proceso una vez que el usuario decide proceder al pago.

### 💳 Microservicio de Pago
Maneja todo lo relacionado con las transacciones financieras de la plataforma, incluyendo la integración con WebPay.

#### Funcionalidades Principales
💰 Proceso de Pago: Gestiona el proceso de pago de un pedido, facilitando la transacción entre el cliente y la plataforma.
🔗 Integración con WebPay: Permite pagos a través de tarjetas de débito y crédito utilizando WebPay.

### 🆔 Microservicio de Autenticación y Autorización (Usuarios)
Gestiona las operaciones relacionadas con los usuarios, desde la creación de cuentas hasta el inicio de sesión y la autorización.

##### Funcionalidades Principales
📝 Registro de Usuarios: Creación de cuentas y verificación de correo.
🔐 Inicio de Sesión: Autenticación de usuarios.
🔑 Gestión de Tokens: Generación y validación de tokens.
❓ Recuperación de Contraseña: Proceso de recuperación de contraseña.
📊 Actualización de Perfil: Modificación de detalles del usuario.
🛂 Autorización: Verificación de permisos del usuario.

### 🌐 API Gateway: Centraliza las solicitudes y dirige el tráfico a los microservicios correspondientes, implementado en Golang.

## 👁️ Vistas incluidas:
📖 Navegación de productos.
🔍 Detalle del producto.
🔐 Inicio de sesión y registro.
⚙️ Administración de cuenta de usuario.
📜 Historial de compra.
💰 Checkout y procesamiento de pago.
✅ Resumen de compra.

## 💾 Base de Datos
Utiliza MySQL para persistencia, con diseño y estructura optimizados para operaciones de E-commerce.
