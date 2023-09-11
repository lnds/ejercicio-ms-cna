Curso: Cloud Native Applications - U. de Chile.
Profesor: Eduardo Diaz
Tarea 0 
Participante: Viviana Poblete López 
Caso: CrafStore, Artesanos 


Para modelar los microservicios, podemos considerar dos formas: capacidades del negocio, arquitectura de la aplicación. La propuesta que se plantea consiste en la distribución de funciones, responsabilidades claves del sistema:
1.	Registro, autenticación y validación de artesanos:
a.	Microservicio de registro y validación 
b.	Microservicio de autenticación
2.	Catálogo de productos 
a.	Microservicio de inventario
b.	Microservicio de catálogos
3.	Portal de compras. 
a.	Microservicio de carrito de compras
4.	Ordenes de compras. 
a.	Microservicio de gestión de órdenes de compras.
5.	Despacho de productos.
a.	Microservicio de despacho de órdenes, y gestión de todas las funciones que implica.
6.	Facturación 
a.	Microservicio de facturación y pago mensual a los artesanos.
7.	Aplicación móvil 
a.	Microservicio para acceder a catálogos, órdenes de compras, pagos, seguimientos de compras.
8.	Aplicación para artesanos
a.	Microservicio para los artesanos, quienes podrán administrar catálogos, y recibir notificaciones. 
Cabe señalar que los microservicios se podrán comunicar a través de API, la elección de las herramientas y tecnologías específicas dependerá de los aspectos técnicos y preferencias del equipo de trabajo, cuyas funciones serán asignadas al iniciar el proyecto y avanzar en el desarrollo de las funcionalidades de la aplicación. 
El uso de API permitirá trabajar y procesar entre las distintas plataformas definidas por el equipo de trabajo.
