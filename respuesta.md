Integrantes del grupo: Rocío Contreras Águila - Brebdgary Valenzuela

Haga una descomposición por dominios o por capacidades del negocio y de acuerdo a esta proponga la arquitectura de micro servicios inicial. Dibuje un diagrama con los micro servicios involucrados, dibujando interconexiones entre estos, si es que son necesarias. Deje este dibujo como un archivo PDF, PNG o JPG, junto con su respuesta. Considere micro servicios genéricos y las integraciones con terceras partes.

Liste los micro servicios necesarios y por cada uno describa su función principal.

  - Registro y Validación de Artesanos.
  - Gestión de Catálogo de Productos.
  - Compras de Productos.
  - Gestión de Usuarios (Compradores).
  - Procesamiento de Órdenes de Compra.
  - Integración con Plataformas de Pago.
  - Notificaciones y Comunicación.
  - Coordinación de Despacho y Logística.
  - Contabilidad y Facturación.
  - Contenido Multimedia y Blog.
  - Tienda de Merchandising.
  - Aplicación Móvil para Compradores.
  - Aplicación Móvil para Artesanos.

La función principal sería:

    - Microservicio de Registro y Validación: Se encarga del registro y validación de artesanos. También gestiona la autenticación y autorización de usuarios.
    - Microservicio de Catálogo de Productos: Permite a los artesanos gestionar su catálogo de productos, incluyendo descripciones, imágenes, precios y stock.
    - Microservicio de Compras: Gestiona el proceso de compra, incluyendo la creación de carros de compra, la división de órdenes por artesano y la integración con pasarelas de pago.
    - Microservicio de Usuarios: Administra los perfiles de los usuarios registrados, incluyendo compradores y artesanos.
    - Microservicio de Procesamiento de Órdenes: Se encarga de procesar las órdenes de compra, notificar a los artesanos y gestionar el estado de las órdenes.
    - Microservicio de Integración de Pagos: Maneja la integración con plataformas de pago como PayPal y Stripe.
    - Microservicio de Notificaciones: Envía notificaciones por correo electrónico y otras formas de comunicación a compradores y artesanos.
    - Microservicio de Logística y Despacho: Coordina el despacho de productos desde los artesanos hasta los compradores a través de una API de courier.
    - Microservicio de Contabilidad y Facturación: Administra el dinero recaudado, genera liquidaciones mensuales y procesa la facturación electrónica.
    - Microservicio de Contenido Multimedia: Almacena y sirve contenido multimedia, como videos de entrevistas con artesanos y contenido del blog.
    - Microservicio de Tienda de Merchandising: Gestiona la tienda de merchandising propia de CraftStore.
    - Microservicio de Aplicación Móvil para Compradores: Ofrece funcionalidad a los compradores a través de la aplicación móvil.
    - Microservicio de Aplicación Móvil para Artesanos: Proporciona funcionalidad a los artesanos a través de la aplicación móvil.

Indique cuantos equipos necesitaría para soportar este desarrollo.
  Para desarrollar y mantener esta arquitectura, se necesitarían varios equipos, uno por cada microservicio. Cada equipo debería ser responsable de su propio microservicio, lo que permitiría la autonomía y la escalabilidad del desarrollo y de la gestión de éstos.

¿Que patrón usaría para gestionar el tràfico entrante: API Gateway o Backends x Frontends? Justifique su respuesta

Para gestionar el tráfico entrante, se puede utilizar un patrón de API Gateway que centralizaría la entrada y el enrutamiento del tráfico a los microservicios, simplifcaría la gestión de las solicitudes de clientes y permitiría la implementación de funciones de seguridad, monitoreo y control de acceso de forma centralizada.
