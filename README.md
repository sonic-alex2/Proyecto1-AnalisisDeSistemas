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

 
 
 # 2. Documentar el análisis (Developer Team)

A continuación podemos iniciar el análisis del Diagrama Entidad Relación. 
(imagen)
<p align="left">
   <img src="[https://photos.app.goo.gl/fieKKVXBe1CQ4xVY8](https://lh3.googleusercontent.com/IeFDuSAdmORJwjquG40rMlPKk3S2eWJJ_8HiaA7Aee0fDt6bFIhfmLy9GW1ZeUzAvQEYqVTzLQnflOx4cQmOBLaj-Atns7v-rVsFy3z8Mw3FyyPj317eqiZLNzqyDouGmZoumqxJoZtgl5YBGxoky6Qtz9XWcury237THzvNFX4_q74b-kez71EbIGiENfZGWNT0e8sMb3ThlN6QTvOrS-HXZ4zXZFtni9C9DDi596rVsbiSAiIXBWRsDqnWOSvwHXlXYJ_Pxa8737KqxtBOrj3kpRIy_YChvpA3bQcuaPN8N2dJES-4PF2UnwP17kERA8Gf9usmRcJFIvcYN5HCY90TRFkhcHtcvbnTknMNBbRYxZVGyoMXDkTIaPhuAGkdH9AdBZOVTgLNwOPqy4gdO5mTf_sJ34ulSzaddnf4CJAm1dcv1Oirs6T5P0vL1d58MORnzGEBHySg3LgbD_wcGBV0gjX8FROZTF_2SDvQ59rJVFW28XtQsEl4JX0bsq54LddAIHmoltr5eh0LEthb0AlyOZYSxeNx3K1YXcHXpmcsuE6MNPBSIQZGJd9S2zemdG0cyjUloMr6_uCizbSiRq6Mdwe10VH6bFN7FbJavHh1nDRp8tFCI1bJp73O6pkl6Ab1u0XF7yVxGlNOur6LQBKlbVuCiEi6uOM47zUQzAWvIkWtu2rZg_4_DGUmx4sgeU-E5XjjcNIWty981Y1gWDAMUTJgL7GJ-zoA0mDCzHKu7TPwEgoaHtSbvkwAfHPH41sV1FRvyJi8uIkM6xqqAmI8jXaulrWRwp6pSUe4SAjLUzEL5qqgTxU6Bura5tQiGaQBzPZuJwUE6XUpm7xU1pVAAiwGzEx0W61y8HLScHmcA3xVMrckYP58RVWpRcoBftAmwIGxP-i6E3KNCCS7tEZod5HZnYzE0DT1aUg1k2gf-zDryRb0oITcpgzw8XPntXVHmzaSfjXAUzyGCw0C3y659qMubqAZJ43ljcFZuFYr6AZAThMTELE=w559-h469-s-no?authuser=2)">
</p>
 
En el archivo se agregan mas.

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
   <img src="https://photos.app.goo.gl/VckAwCAMS2r1rZMB7">
</p>


Órdenes:
(imagen)
<p align="left">
   <img src="https://photos.app.goo.gl/k9tYU3jZTm2LYCJS9">
</p>


Más detalles del aplicativo con respecto a la interfaz:

https://www.figma.com/proto/L0qbS2mcAlt19BYiPc4x28/LAUNDRY.COM?node-id=14-181&scaling=scale-down&page-id=0%3A1&starting-point-node-id=1%3A3
