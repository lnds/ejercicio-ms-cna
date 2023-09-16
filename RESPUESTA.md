# Curso Desarrollo de Aplicaciones Cloud Nativas
> Kevin Beltran C.

## Actividad 1 - **“CRAFTSTORE”** : *Sitio web que permite la compra y venta de artesanía en línea.*

## 1. Dominios y Microservicios

- **Dominio Artesano:**
  - Registro de Artesano: Registro de artesanos en plataforma.
  - Gestion de Producto: Gestion de productos que vende X artesano.
- **Dominio Cliente:**
  - Registro de Cliente: Registro de comprador en plataforma.
  - Gestion de Cuenta: Actualizacion de datos comprador, recibir ofertas, participacion de eventos y promociones.
- **Dominio Compras:**
  - Carro de Compra: Seleccion de articulos del comprador para su posterior compra.
  - Visualizacion Producto: Vista de productos ofrecidos por los artesanos.
  - Gestion de Compra: Datos del comprador y producto. Visualizacion de comprar previas.
  - Integracion API Plataforma Pago: Integracion de distintos medios de pagos (Paypal, Redbanc, Flow, etc)
- **Dominio Envio:**
  - Gestion de Despacho: Datos de entrega de productos.
  - Integracion API Courier: Integracion de empresa responsable de la entrega del producto (Bluexpress, Chilexpress, Starken, DHL, etc)
- **Dominio Entrevista:**
  - Visualizacion de Entrevista: Vista de videos al publico general dentro de plataforma.
  - Gestion de Entrevista: Datos varios del contenido publicado.
- **Dominio Blog:**
  - Gestion de Blog: Datos varios del contenido publicado.
  - Gestion de Merchandising: Visualizacion, venta y gestion general del merch. Enlazado al dominio de compras.
- **Dominio Pago:**
  - Administrador de Venta: Administracion de ingresos a plataforma.
  - Administracion de Pago: Administracion de pagos al artesano.
- **Dominio Movil:**
  - Integracion API Movil: Integracion de API REST o EndPoints para el uso de datos almacenados.

## 2. Equipos necesarios para el desarrollo

- 1 Equipo por cada 2 Dominios para facilitar el desarrollo, seguridad y escalabilidad de cada uno.
- 1 Equipo QA por cada 2 equipos de desarollo para el seguimiento de cumplimiento de seguridad, ux, ui, entre otros.
  
## 3. Patrón para la gestion de trafico entrante: API Gateway o Backends x Frontends

Api Gateway, ya que puede servir como un punto de entrada único para microservicios, lo que facilita la gestión de rutas, autenticación, autorización y monitoreo.

## 4. Diagrama con microservicios involucrados

![Diagrama con microservicios involucrados](https://github.com/kebeltranc/ejercicio-ms-cna-00/blob/main/Diagrama.png)
