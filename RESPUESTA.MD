Liste los micro servicios necesarios y por cada uno describa su función principal.

Dominio: Registro y Validación de Artesanos 
* Microservicio de Registro de Artesanos: Gestiona el registro de nuevos artesanos y la validación de sus antecedentes comerciales.
* Microservicio de Validación de Antecedentes: Realiza la validación de los antecedentes proporcionados por los artesanos.

Dominio: Gestión de Productos 
* Microservicio de Gestión de Catálogo: Permite a los artesanos gestionar sus catálogos de productos, incluyendo descripciones, fotografías, precios y stock.

Dominio: Compras y Ventas
* Microservicio de Compras: Administra las compras realizadas por los usuarios finales en el portal público, incluyendo la creación de órdenes de compra para los artesanos.
* Microservicio de Órdenes de Compra: Administra las órdenes de compra, dividiendo las compras en órdenes individuales para cada artesano involucrado.
* Microservicio de Notificaciones: Envía notificaciones a los artesanos con las órdenes de compra que deben completar.
* Microservicio de Despacho: Coordina el despacho de los productos desde los artesanos hasta los clientes a través de la empresa de Courier.

Dominio: Usuarios y Cuentas 
* Microservicio de Usuarios: Gestiona la información de los usuarios, incluyendo registro, autenticación y perfil.
* Microservicio de Perfil de Usuario: Administra los perfiles de usuario, incluyendo historial de compras, suscripciones y participación en eventos y promociones.

Dominio: Contabilidad y Pagos 
* Microservicio de Contabilidad: Administra el dinero recaudado, genera liquidaciones mensuales y realiza pagos a los artesanos.
* Microservicio de Facturación Electrónica: Permite a los artesanos subir facturas electrónicas para recibir el pago.
* Microservicio de Pagos: Integra diversas plataformas de pago como PayPal y Stripe para procesar pagos de los clientes.

Dominio: Contenido y Medios
* Microservicio de Contenido Multimedia: Administra videos de entrevistas a artesanos, blogs de decoración y la tienda de merchandising propia.

Dominio: Aplicaciones Móviles 
* Microservicio de Aplicaciones Móviles: Proporciona servicios necesarios para las aplicaciones móviles de Android e iOS.
Integraciones con Terceros
* Microservicio de Integración con Empresa de Courier: Se integra con la empresa de Courier a través de una API para coordinar el despacho de productos.

Indique cuantos equipos necesitaría para soportar este desarrollo.

Dejariamos al menos 3 equipos de desarrollo que estén a cargo al menos de 2 dominios cada uno

¿Que patrón usaría para gestionar el tràfico entrante: API Gateway o Backends x Frontends? Justifique su respuesta
Dado que hay algunos dominios que no son de acceso público y otros a los cuales no son de consumo de todos los otros backend, dejaríamos un API Gateway que sea el encargado de gestionar las credenciales para el acceso seguro a los diferentes backends.


