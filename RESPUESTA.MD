Grupo1: 
+Ignacio Gonzalez
+Francisco Parra
+Felix Cifuentes

1. Liste los micro servicios necesarios y por cada uno describa su función principal.

# Api Gateways:
* Frontend Web
* Aplicaciones Mobiles
* Aplicaciones de terceros con terceros

# Dominios

Dominio de Artesanos:
* Servicio de Catálogo de Productos: Permite a los artesanos gestionar su catálogo de productos, incluyendo descripciones, imágenes, precios y stock.
* Servicio de Gestión de Órdenes: Controla las órdenes de compra y notifica a los artesanos sobre los pedidos pendientes.

Dominio de Usuarios:
* Servicio de Autenticación: Gestiona la autenticación de usuarios y la gestión de tokens.
* Servicio de Usuarios: Administra la información de los usuarios, incluyendo perfiles y preferencias.
* Servicio de “Historial Compras”: Administra el historial de compras y notificaciones de ofertas para usuarios registrados.

Dominio de Compras y Ventas:
* Servicio de Carrito de Compras: Administra el carrito de compras de los usuarios, permitiendo la agrupación de productos de diferentes artesanos.
* Servicio de Compras: Maneja el proceso de compra, integración con pasarelas de pago .
* Servicio de Despacho: Coordina el envío de productos desde los artesanos hasta los compradores a través de una empresa de Courier mediante una API de terceros.

Dominio de Contenido Adicional:
* Servicio de Contenido Multimedia: Gestiona el contenido multimedia, como videos de entrevistas, el blog y la mini tienda de merchandising propio.

Dominio de Finanzas:
* Servicio de Liquidación de Pagos: Administra los pagos y genera liquidaciones mensuales para los artesanos, incluyendo la recepción de facturas electrónicas.

Integraciones Externas:
* Integración con Pasarelas de Pago: Interactúa con pasarelas de pago como PayPal y Stripe.
* Integración con API de Courier: Conecta con la empresa de Courier a través de una API de terceros.
* Integración con Módulo de Facturación Electrónica: Permite a los artesanos gestionar las facturas electrónicas.

2. Indique cuantos equipos necesitaría para soportar este desarrollo.

Para soportar este desarrollo, se necesitarían al menos los siguientes equipos:

Un equipo de desarrollo:
*  para cada uno de los microservicios mencionados anteriormente, compuestos por desarrolladores, probadores y posiblemente diseñadores de interfaz de usuario.

Un equipo de operaciones y administración de sistemas:
*  para gestionar la infraestructura de microservicios, la escalabilidad y el monitoreo.

Un equipo de seguridad: 
* para garantizar la seguridad de la plataforma y los datos del usuario.

3. 
