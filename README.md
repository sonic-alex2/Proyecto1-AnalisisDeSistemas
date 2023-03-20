# 1. Documentar los requerimientos (product owner - backlog)

A continuación podemos documentar los siguientes requerimientos para poder filtrar lo más importante a la hora de realizar el análisis según el modelo de cascada.

# Será necesario lo siguiente:

- Un apartado para `Servicio`s con 2 tipos de lavado (seco, lavadora).\
-- Será necesario un input(caja que permita texto).\
-- Un botón de crear un nuevo servicio.\
-- Un botón para guardar un nuevo servicio.\
-- Un apartado que muestre el listado de los servicios que fueron agregados.\
-- Un botón de editar el texto del servicio agregado.\
-- Un botón que muestre detalles de ese servicio.\
-- Un botón para eliminar algún servicio que se agregó con anterioridad.\

- Un apartado para la `prenda`.\
-- Será necesario un input(caja que permita texto).\
-- Un botón de crear un nuevo prenda.\
-- Un botón para guardar una nueva prenda.\
-- Un apartado que muestre el listado de las prendas que fueron agregadas.\
-- Un botón de editar el texto de alguna prenda agregada.\
-- Un botón que muestre detalles de cada prenda.\
-- Un botón para eliminar alguna prenda que se agregó con anterioridad.\
- Un apartado para `Cliente`s debe de llevar: id, nombre, apellido, (domicilio:calle|número|apartamento|piso), número, apartamento y piso. barrio y el teléfono.\
-- Será necesario varios  input(caja que permita texto).\
---- Para el nombre.\
---- Para el apellido.\
---- Para la calle.\
---- Número de apartamento.\
---- Para el Piso.\
---- Para el teléfono.\
---- Para el barrio.\
-- Un botón de guardar a un cliente.\
-- Un botón de crear un nuevo cliente.\
-- Un apartado que muestre el listado de la información que fueron guardados relacionados a los clientes.\
-- Un botón que muestre detalles de cada cliente.\
-- Un botón de editar el texto del cliente agregado.\
-- Un botón para eliminar algún cliente que se agregó con anterioridad.\
- Un apartado para Pedidos (`Orden`es): id, fecha pedido, tipos de prenda, tipo de servicio individual, cantidad de prendas para ambos servicios, precio total, status de cada pedido.\
-- Será necesario varios  input(caja que permita texto).\
---- Para la fecha de pedido.\
------- Entrega +90 días no se entrega nada.\
---- Para tipos de prenda.\
---- Para tipo de servicio individual.\
--- Estatus de cada pedido.\
--- Un botón para generar detalles.\
--- Cantidad de prendas.\
----- Pagos solo en efectivo.\
--- Un botón de guardar la orden.\
--- Un apartado que muestre el listado de la información que fueron guardados antes de los clientes que fueron agregados.\
---- Un botón de editar el texto del cliente agregado.\
---- Un botón para eliminar algún cliente que se agregó con anterioridad.\
- Un apartado donde liste el reporte mensual de prendas más solicitadas y su tipo de servicio.\

 
 
 
 
 
 
 


# 3. Documentar el diseño de la aplicación (Developer Team)

## 3.1) Requerimientos Funcionales:

R1: El sistema debe validar si el cliente existe dentro de la base de datos.

R2: El sistema debe incluir el tipo de lavado seco.

R3: El sistema debe incluir el tipo de lavado en la lavadora.

R4: El sistema permitirá actualizar el tipo de servicio de la lavandería.

R5: El sistema permitirá eliminar el tipo de servicio de la lavandería.

R6: El sistema debe permitir al administrador generar pedidos para los clientes.

R7: El sistema debe permitir al administrador generar ticket al cliente.

R8: El sistema debe generar un bitácora mensual con los tipos de servicios más solicitados.

R9: El sistema permitirá generar facturas.

R10: El sistema permitirá crear el tipo de prenda de la lavandería.

R11: El sistema permitirá actualizar el tipo de prenda de la lavandería.

R12: El sistema permitirá eliminar el tipo de prenda de la lavandería.

## 3.2) Requerimientos No Funcionales:

(Datos que no son directamente funcionales con la aplicacion) producto externos, etc.

RNF1: El aplicativo es orientado a la web llevando el modelo cliente - servidor.

RNF2: La arquitectura que contiene el proyecto es M.V.C.

RNF3: El software se desarrolla con el lenguaje HTML5 ,CSS3 y JavaScript.

RFN4: El aplicativo se desarrolla en JAVA y JavaScript.

RNF5: La aplicación corre en navegadores Mozilla, Google Chrome y Navegador Edge.

RNF6: La base de datos que administrará este aplicativo es PhpMyAdmin 5.3

RNF7: El servidor a utilizar en el aplicativo será XAMPP 7.2.11


## 3.3) Acerca del prototipado:

Home:

(imagen)
<p align="left">
   <img src="https://lh3.googleusercontent.com/Dsx6LK2F09n1MBvmrDEx3dOnHiQHOF2HHgIAOGHpFeeGTBNrY-uybj5Rsygus_GtrEMq6KCvtDcXnndr_4aJ_fqT2VfHmxxkg83FKGoUUKR7ncga-wMeduJQ7pfuNViCFCYukHhrXYb_SN_uVzqfKwu-kA579dixlqQhwfA3U9KW433goa3IWY_QwoRpAFp7_WJokQ4wqqvMoozYPwiZi2ARCMr8L4_WVi6_oJb0kPjZtft-LIbMoc_4GrOpDWASAveaOht61Vuj-C3BugYOPASA48GvUHTlMn60d5n__n9Zki_8IuWvFWq2XsFZx3bsRtmmH9b_MXK4kPi1bDq45NPdH6zzA5JHhlD-QLSXY_G8I-Ay4a15P6QzdjqoBgVhTESZLU0k-5OkpVgh5tPf6B7NzHxQBI-JednvGndEEc-CELmzvfAAaHQ9Yzusu_ZNfo9hJV0WzfY84C3mmvhaK7Do8oCIvwBlxCaXHWeZwyzqVPLVVT3yT8Fhb5_BgGF5dtd6lAuX-mjnwrR3j_Mo-j2O-x8dtFdhJv-RIyUs90LvqJrCoa0j7wwBo5d3wqVjTPl1od_pqjHf6JeqMIhrHQKgmwLsdfoExfWtVf-RC4VBHRYHB5bD8u9v4ywzRrzVnTNMV4qULQiSViXtl7dla5OrlOiKYsQOCqbzYb6mqMQGaWPPaiiMSvshuBxjepbdnQyPHcAJG1SgLu9zRBj3xocxYAW7aRgtcIXsIQONvvaogp0KOZugYMeUOhs63RqowRXC77DkbneolQm_H34Md_a8pdk_m7mk_vE1asycitkkqbdYJzeoPitGLwrLvntnMBG9OaqClIIJnL2HNRx3N6uHJWqmzBl0LD8cpaBTq31_ogvnn5iviIduuPIQnO7pn46SxlDpyD32uuAJ3zoOM8PutLf3B1vPEzpV5AcmX_Gg3cpSKQNICHwtlfAjM66bPa0NYv5Pv-OBmHV3CaUJYwxBMosTRoPJuohsVObDVHObWq_ArqaEjzo=w1027-h276-s-no?authuser=2">
</p>


Órdenes:
(imagen)
<p align="left">
   <img src="https://lh3.googleusercontent.com/VuYkEsNWNRxg5VZ27taUK4SWfOGW3PzTd5iWcMsVEP794Sb9VSTXrGH4WFEUkvaxREhRjXNq6LLfdUtcsXuiWjrYoeh0GmJT-inpy0rP_4lA-52HIAL5g8A0DWvBbP0iLCuk3Txed7qLkN81ov8o9we5pgqcTqHCiDiS-PPKmfnfYvGFjejNlWJXPnTffKwRz3dS0Dr5NOsTwcU8A0CBeB9DYchb9E04kq0MqHLUrWb2VmscGPAY0dnoKhc8X7wSkH9_65swnV8KciaS4XAZrtb0aOjPKIF6GQwf6hbcvmKfTBog-k3vfFA_qb39n0IBeHO5dYU7F0pI4G9FlHluiNzp_EsHQtLa1jLKV6ZdsuTsR67thw7rEJLe9lIFsoutJMdvh-SDZNheCfiaCdjVmu2-4rmOVASM5bI31w75NleMVq3w9NXjr5s-zBxlSJ0Vqst-3I8JC0j7ph95HEc8WntQaIFZkQkaEm-N8EZgqDppiAd2qSMf97GXL_ii9KWDlNLB5En1s4ZR0bWWvb0UVwqfXsIQruCYCAlT6h-iGZhXofB-TuLiIiKNgpI1f6uQQjcY-qaoVlE8oZYhAV_RQbS7KweRGhq6HMdhjXIOA6Er7t0DLPCeI3sApQvhCYTW62sKsUI5_9XUiuG0UcNJXQ3TNCUGb9k1WXUzXEXAwIP2fnY51eM6EVxlzy1L1UZEIe0iywN2fKyocleL2bPGdANwMmLhmv0GxzwtjSJBStnXsW5WfTuqPG8u8Psscapyz0FvoeAzKp_QuVMi68TWhASqMoeg-WrfY-4SRdI04eIT3r-uUSTR68W2GNJJwKbR1BoQBrLu8_4pV9UbHpXnE3Fz0RsSh_q46kRvVKYU8PiK7Rg5Yjv0G9CHnpssfGA3Z46UejJWMkPCwQgunHtPIocSsNnUXXRvjQhr8U08SACJjgsQ7iN5Qj_nrXSfYZt02jPsXInjPg0KCphSagtVrtlNMNMk_71jlbRWPhiDngDffXitRgrOAQU=w994-h586-s-no?authuser=2">
</p>


Más detalles del aplicativo con respecto a la interfaz:

https://www.figma.com/proto/L0qbS2mcAlt19BYiPc4x28/LAUNDRY.COM?node-id=14-181&scaling=scale-down&page-id=0%3A1&starting-point-node-id=1%3A3
