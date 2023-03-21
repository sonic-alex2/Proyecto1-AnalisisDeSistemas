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
   <img src="https://lh3.googleusercontent.com/IeFDuSAdmORJwjquG40rMlPKk3S2eWJJ_8HiaA7Aee0fDt6bFIhfmLy9GW1ZeUzAvQEYqVTzLQnflOx4cQmOBLaj-Atns7v-rVsFy3z8Mw3FyyPj317eqiZLNzqyDouGmZoumqxJoZtgl5YBGxoky6Qtz9XWcury237THzvNFX4_q74b-kez71EbIGiENfZGWNT0e8sMb3ThlN6QTvOrS-HXZ4zXZFtni9C9DDi596rVsbiSAiIXBWRsDqnWOSvwHXlXYJ_Pxa8737KqxtBOrj3kpRIy_YChvpA3bQcuaPN8N2dJES-4PF2UnwP17kERA8Gf9usmRcJFIvcYN5HCY90TRFkhcHtcvbnTknMNBbRYxZVGyoMXDkTIaPhuAGkdH9AdBZOVTgLNwOPqy4gdO5mTf_sJ34ulSzaddnf4CJAm1dcv1Oirs6T5P0vL1d58MORnzGEBHySg3LgbD_wcGBV0gjX8FROZTF_2SDvQ59rJVFW28XtQsEl4JX0bsq54LddAIHmoltr5eh0LEthb0AlyOZYSxeNx3K1YXcHXpmcsuE6MNPBSIQZGJd9S2zemdG0cyjUloMr6_uCizbSiRq6Mdwe10VH6bFN7FbJavHh1nDRp8tFCI1bJp73O6pkl6Ab1u0XF7yVxGlNOur6LQBKlbVuCiEi6uOM47zUQzAWvIkWtu2rZg_4_DGUmx4sgeU-E5XjjcNIWty981Y1gWDAMUTJgL7GJ-zoA0mDCzHKu7TPwEgoaHtSbvkwAfHPH41sV1FRvyJi8uIkM6xqqAmI8jXaulrWRwp6pSUe4SAjLUzEL5qqgTxU6Bura5tQiGaQBzPZuJwUE6XUpm7xU1pVAAiwGzEx0W61y8HLScHmcA3xVMrckYP58RVWpRcoBftAmwIGxP-i6E3KNCCS7tEZod5HZnYzE0DT1aUg1k2gf-zDryRb0oITcpgzw8XPntXVHmzaSfjXAUzyGCw0C3y659qMubqAZJ43ljcFZuFYr6AZAThMTELE=w559-h469-s-no?authuser=2" alt="imagen entidad relacion, no se ha podido cargar la imagen.">
</p>

A continuación incluimos el diagrama de clases.

<p align="left">
   <img src="https://lh3.googleusercontent.com/pw/AMWts8BPtjBBjm_48VA9DWPC0E9UkOoRQ9-xOnHjke6Bv-H3x4oyDvG4dcqbdBkdbyuBjJpD8nYmQGVJ3tVqfBw0K46JsjZi87K9weYdwQMRxXEUd_xNUsB5P_BBSJNkmMVphQEM7zhVS3uZ7dKp0_uI8HY-=w848-h923-s-no?authuser=2" alt="imagen diagrama de clases, no se ha podido cargar la imagen.">
</p>

A continuación También el diagrama de flujo de la entrega más de 90 días

<p align="left">
   <img src="#" alt="imagen diagrama de flujo, no se ha podido cargar la imagen.">
</p>

El link donde se puede encontrar el diagrama de flujo.
https://umgt-my.sharepoint.com/:u:/g/personal/jramosp15_miumg_edu_gt/EY6_eNFvhXdLv6
kAUAdJriYBO1fyytUCoZ7mHe244bIXgQ?e=kiROEX
 
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
   <img src="https://lh3.googleusercontent.com/0d8CeVvFlNXkSFeUx8lTrlCIhXHTAEtvvHUSdQ4Meuw0IKUrzD9h-6W4LwwvSqABrQexrTApLZJ1FY_xFs_mQluRqdr05zPvvK0lav8bPtsRWfR22s4oUnpyMKyR4U4isYxwbP3pFqXCxLeK56p-LA0JQ8u8o_0DsS8H_HcQBzCgtsEiKFf8PX0FHGZouUeo4BTNBmPh2YjEKkUDwojrme9WXi-TXWmjkvKBSUoa6HIrJpGRd2XjU3DrPm50Ku_Q0LTT5sDKdScI5CtCgiciSEjvBHochwGzDmskjOW7OJi964bz69I93sUVTr2BO87iHkqwz7Ruhz634S4bGwuFV8fXnLDgINRGwU3zqGKIPgljsb-zPV1DKGiOZS7SMm_F-7xhecTt3jcpE7Z19zwtshsVbH_91vtAXg4Seedh_n0nN7opg-ABj0csAD4RUM40bvVeM6B3ZXJxdyBk1BmbmutWXuiU1DGfZWSg4KOSWQoTtk-cz9eICG5bMpglnd3jkM1dY8Ev5HDMGJpwY2MvdcIezhyAY0VizgZe9rNxuieUsSRDN2WjNg-Q3NCbF1_cesWSxOYi4zNrSFE8bQxmDxeEsmh5ZEFX61qnqNh3AQGhmQwteVORk9Z4z-NbAqIH2MWbVwUU-hkOUzjktf4b5tkaOolz4sMUxAAZ84LTG-X8WUgOCWnQDLw0-7TwNbLbM6AoVtAYNZ5bPfOp4DwZgixyTcIbT5-ip7XzPQh_jK1_YcBpds-hyE6b_i8euSKtOg9TGpLkkptCDBhzny_rxBj8B6rrdoHEUaYbzB7DgYKWzj8nPE0BDxL0lurWjtzJomS4V4o53ET8UUxopbEPq0ZMV3eSAY8stMrntrLnJQouaeFg8yzhgw0B_mrYdQ5BBBcQiknlpNPYG6dtP-m8kCeQ4VTqGaiVUugC6E9XrEAGIczPbW5s5jNelEPzPfrQGMW3v17MBkW4wqBZ5bfIOQShRNUXeRkr8mF8s-RoEJZBeUlJXlgIKrY=w1027-h276-s-no?authuser=2" alt="imagen home de la aplicacion, no se ha podido cargar la imagen.">
</p>


Órdenes:
(imagen)
<p align="left">
   <img src="https://lh3.googleusercontent.com/8W60ZBsY0XvP2RLH_EGPp16zG0nrfLy4TBpVOwzsUum3K1b91-wWdErPYaKj6FiZ3BNpiNpojjDBP3gAGDyVvsoVTz5NPJeBR7Kv2ywEODABj80byZb40Lg-5Ev2cez9_NEA74qUMMwRYbqTTLumdSx0-41y8xI_coMl4SGS3v42CMR06e3FdXJ0iiqFdBQxsYnZMjyuA-EzkzUfzVnn4HV8WqxtE_wO4QaGFC43pD6YC2hc6SmgKafjtH_YK5AOHDxgk_F46OoZrCLUC43Tgm2lsRpqpZgVfWz5RWNqsMbb2UMBVWD3E03sR73JnAiYj5DvAmQ74LQwH9z-OUi2S23WmcaWqwJaxiLPvXULwKoPZzFzJJiviKFsg1ZX9b-sxRgwRmB8LK-4jG7fPnxoOGFC-j2JvEJ5Myuf7RKU52KtJ4RmY8R_a1kSI-TfaTceKeiR1OhCAp5MoKZWJcucIXZjlRy2sC1kCIC1NT-JQZy9vg9xqGerWXh1ohGhw1jP0TaJsfJTzOUnO11U2n390fSmmFVmOAdaS0DPvoJN-sPPOptyGyeAPffqd4HW31t7L5JtbMMHFpzxiSe33z9eSjWYpZRY2R5s0zrDvgMaqhcfEsVanIBx6H6X9WrJxS4mAmidqN2fFMVZ7PfSCamYAMKiLpZ-ku2-csGzAhViNq1WpROkBv4aqRbFjasAYrf6hLIchRIXnb86afIgOpXFHXCZ03ofwW5yOym-lEeEPpEcVw70a5VsLTrYHeICovnt6AkrWY-JEEI_I8KoWJBoXB0KBcXf6mM2DqmT4Yp7i--NEe0Rd17ukXLSKRJiKhwMPtGz36cEggw56umExothMzvLBJ5TnkoamKguiLDOEREKMm6eSPBbG8qmuYzsgBqlkNApXEEsorVQnTu9ZVeZAMTM1ard2TgnygPcVgghO34iT1TrlLt4y11UEDTLiK9nV8IMo2qraeudyaE7zioSxTO0eZu1ZOSu1f-EKW_Arkff4g5-UUSRZuY=w994-h586-s-no?authuser=2" alt="imagen de ordenes, no se ha podido cargar la imagen.">
</p>


Más detalles del aplicativo con respecto a la interfaz:

https://www.figma.com/proto/L0qbS2mcAlt19BYiPc4x28/LAUNDRY.COM?node-id=14-181&scaling=scale-down&page-id=0%3A1&starting-point-node-id=1%3A3


# 4. Elegir una metodología de desarrollo (En cascada - Con una variante de Scrum

<p align="left">
   <img src="https://lh3.googleusercontent.com/pw/AMWts8Ath6gteCBqunHwm72pnm7ER7qvsjdVe4Bubltm1Wwb8ijKgZMypu5mZ3Xzi06VpUrVBdEiO9TH2rQueaE0qGl9T2qN0YzXlGelvk6ul-Mrac07ERZNgr9GRiBQ_Akc-RFCkyNP6JZqEoRiW1ZlUyXv=w679-h399-s-no?authuser=2" alt="imagen metodologia en cascada, no se ha podido cargar la imagen.">
</p>

# 5. Documentar las pruebas
Está en fase pendiente, aunque se agregó al cronograma, y se realizarán las pruebas de funcionalidades en los puntos arriba mencionados.
	

# 6. Documentar la implementación.

	Está en fase pendiente, esta será después de la fase anterior. y agregaremos los detalles sobre la implementación, el servidor donde estará etc.
	
# 7. Otras que considere.

A continuación podemos observar el diagrama de Gantt.

<p align="left">
   <img src="https://lh3.googleusercontent.com/pw/AMWts8Bys0qLDwkmsh4XtPdB30pIIUwNxwg6T2bJi66VhDumkh8mxbdt2VLEhWisFzPKw8Xk0-cpmudqbSt1AxA9Y2acYeu692qAwjz5u41G0ZTakOOJ1wNINW0JCYdzipIXsA50cDNNJFyhdIRFCZLGeU6j=w1280-h359-s-no?authuser=2" alt="imagen diagrama de gantt, no se ha podido cargar la imagen.">
</p>

En el siguiente link se puede obtener más información sobre el diagrama.

https://1drv.ms/x/s!AkAMBXHUiRv_kmTj1bKmq2G3df3j?e=1pAVuG

