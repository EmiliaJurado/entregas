# Pedidos y Entregas Emi

## ¿De que trata? 
En esté trabajo se presenta un sistema web de ventas móviles online, facilita el trabajo de los pedidos y entregas de los productos, sin ningún intermediario. TU MÓVIL DIRECTO Y A LA PUERTA DE TU CASA.

## Funcionamiento y configuraciones
|Contiene un Navbar con las opciones siguientes:|
------------------------------------------------
- INICIO: --> Te presenta anuncios de ventas para el  usuario y así mismo productos móviles en venta para agregar a tu carrito.

- PRODUCTOS MÁS POPULARES: --> Te presenta el TOP de los productos mas vendidos, empieza desde el 5 al 3, esto se debe  por la posicion del producto en ventas. Cada producto tiene el NOMBRE DEL PRODUCTO,DIMENSIONES,COLORES DISPONIBLES, y PRECIO DEL PRODUCTO. Mediante la BD, todos los productos estan identificados por un numero de ID que esta por defautl, y  los usuarios ingresados se identifican por una ID que va incrementando en la BD. 

- TIENDA: --> Te presenta las vetas de los móviles para que los puedas añadir al carrito de compras. Cada producto tiene el NOMBRE DEL PRODUCTO,DIMENSIONES,COLORES DISPONIBLES, y PRECIO DEL PRODUCTO. Mediante la BD, todos los productos estan identificados por un numero de ID que esta por defautl, y  los usuarios ingresados se identifican por una ID que va incrementando en la BD. 

- NOSOTROS: --> Te presenta un poco de información para saber el funcionamiento de la empresa.

- ADMINISTRADOR: --> Solo el  administrador tiene permitido acceder a esta página y verificar el pedidio del usuario, como tambien puede subir productos móviles para la venta. 

- REGISTRARSE PARA PEDIDOS: --> Te presenta el sistema de registro,para que el usuario pueda ingresar mediante un login al sistema web "PEDIDOS Y ENTREGAS EMI" y pueda realizar sus compras.

- INGRESAR (Login): --> El usuario podra ingresar con el nombre de usuario y contraseña. Hago mención que el administrador tiene un nombre de usuario y contraseña por default.|


# INSTRUCCIONES DE FUNCIONAMIENTO

## Usuario (Comprador):
- Comienza entrando al INICIO, en el caso de ser nuevo, tienes que registrarse en el apartado de REGISTRARSE PARA PEDIDOS.
- Debe entrar INGRESAR (login), he ingresara usuario y contraseña esos datos se guardaran en la base de datos.
-Meiante un ID creado en la base de datos tendra su identificacion del cliente.
- Te presenta un navar con las opciones:
---------------------------------------------------------------------------------------------------------------------------------------------
 1. INICIO:  Te presenta anuncios sobre promociones móviles para el  usuario y así mismo productos móviles en venta para agregar a tu carrito de compra, cada producto tiene un ID para poder identificarlo. 

- En el caso quererlo, daremos clik en "Agregar al Carrito", nos madara ha realizar el pedidio de la compra, mediante la bd tendremos por default la ID del producto y la ID de la identificación del cliente.
- Colocaremos el color del prodcto.
- Colocaremos el tamaño del producto.
- Clik enviar.
----------------------------------------------------------------------------------------------------------------------------------------------
2. PRODUCTOS MÁS POPULARES:  Te presenta el TOP de los productos mas vendidos, empieza desde el 5 al 3, esto se debe  por la posicion del producto en ventas. Cada producto tiene el NOMBRE DEL PRODUCTO,DIMENSIONES,COLORES DISPONIBLES, y PRECIO DEL PRODUCTO. Mediante la BD, todos los productos estan identificados por un numero de ID que esta por defautl, y  los usuarios ingresados se identifican por una ID que va incrementando en la BD. 

- En el caso quererlo, daremos clik en "Agregar al Carrito", nos madara ha realizar el pedidio de la compra, mediante la bd tendremos por default la ID del producto y la ID de la identificación del cliente.
- Colocaremos el color del prodcto.
- Colocaremos el tamaño del producto.
- Clik enviar.
----------------------------------------------------------------------------------------------------------------------------------------------
3. TIENDA:  De la misma manera tenemos promociones móviles que puedes agregar a tu carrito, y debes realizar el mismo procedimiento para adquirirlo. 
- Daremos clik en "Agregar al Carrito", nos madara ha realizar el pedidio de la compra, mediante la bd tendremos por default la ID del producto y la ID de la identificación del cliente.
- Colocaremos el color del prodcto.
- Colocaremos el tamaño del producto.
- Clik enviar.

-----------------------------------------------------------------------------------------------------------------------------------------------
4. NOSOTROS: Te presenta un poco de información para saber el funcionamiento de la empresa.
-----------------------------------------------------------------------------------------------------------------------------------------------
5. ADMINISTRADOR: Solo el  administrador tiene permitido acceder a esta página y verificar el pedidio del usuario, como tambien puede subir productos móviles para la venta. 
-----------------------------------------------------------------------------------------------------------------------------------------------
6. LAGOUT(salir): Te sacá de la sesión y regresa al INICIO.
-----------------------------------------------------------------------------------------------------------------------------------------------
En el pie de la pagina te da la bienvenida con el nombre de tu usuario y las siguientes opciones: 

1. Administrar Cuenta: Te muestra las ordenes de pedidos que has realizado mediante: 
- ID
- NOMBRE DEL PRODUSCTO.
- MARCA DEL PRODUCTO.
- TAMAÑO DEL PRODUCTO.
- COLOR DEL PRODUCTO.
- PRECIO DEL PRODCUTO.
- FECHA DEL PEDIDO.
- ACCIONES (eliminar).
2. Salir: Te sacá de la sesión y regresa al INICIO. 
3. Volver al inicio: Te dirige al INICIO dentro de tu sesión.
------------------------------------------------------------------------------------------------------------------------------------------------
## Servidor (Vendedor): USUARIO: adminstrador  CONTRASEÑA: 1234abcd..
- En el INICIO del sistema de "PEDIDOS Y ENTREGAS EMI" se encuentra en  NAVBAR la opcion:
1. ADMINISTRADOR: Solo el  administrador tiene permitido acceder a esta página y verificar el pedidio del usuario, como tambien puede subir productos móviles para la venta. 
- Daremos clik en "ADMINISTRADOR".
- Ingresaremos al login.
- Colocaremos el NOMBRE DEL USUARIO: adminstrador y CONTRASEÑA: 1234abcd.. (Estos datos estan por default en la BASE DE DATOS).
------------------------------------------------------------------------------------------------------------------------------------------------
- Te muestra la sesión del "ADMINISTRADOR" mediante el NAVBAR te muestra las siguientes opciones:
1. INICIO: Te  saca de la sesión "ADMINISTRADOR" y regresa al inicio.

2. ÓRDENES: Te muestra las órdenes de los clientes, mediante la ID DE ORDEN ,ID DE CLIENTE,NOMBRE DEL PRODUCTO, MARCA MÓDELO, DIMENCIONES, COLORES DE PRODUCTO,PRECIO DE PRODUCTO, FECHA DE ÓRDEN,ACCIÓN(eliminar).
------------------------------------------------------------------------------------------------------------------------------------------------
3. PRODUCTOS: Podemos agregar productos para vender,y mostraralos en TIENDA, TOP 3,4,5 he INICIO, para eso tenemos que llenar los siguientes datos:
- NOMBRE DEL PRODUCTO. Agregaremos el nombre del móvil.
- MARCA DEL PRODUCTO.Agregaremos la marca del móvil.
- PRECIO DEL PRODUCTO. Agregaremos el precio del producto.
- DIMENSIONES. Agregaremos el tamaño del móvil.
- COLORES POSIBLES: Agregaremos los colores que tenemos disponibles.
- CATEGORÍA: Agregaremos la categoría "CELULAR"
- IMAGEN DEL PRODUCTO: Agregamos una imagen del móvil que pndremos a la venta. 
- Enviar: Se guardaran todos los cambios realizados.
-----------------------------------------------------------------------------------------------------------------------------------------------
4. LISTA DE PRODUCTOS: Se almacenan los cambios que hemos realizado en apartado de "PRODUCTOS" y podremos relizar "Acciones" como editar o aliminar el producto ya creado. Hago mención que todos los productos que hagamos en el Apartado de "PRODUCTO" seran mostrados para vender.
------------------------------------------------------------------------------------------------------------------------------------------
5. CLIENTES: Podemos visualizar:
- ID CLIENTE: Va incrementando en la base de datos según su registro.
- USUARIO: Nombre de usurio con el que ingresan a la sesión.
- CONTRASEÑA: Contraseña del usurio con el que ingresan a la sesión.
- PRIMER NOMBRE: Nombre del cliente.
- PRIMER APELLIDO: Apellido del cliente.
- SEGUNDO APELLIDO: Apellido del cliente
- DIRECCION: Direccion del cliente, para poder enviar su pedido.
- CORREO ELECTRONICO: Correo electronico para poder localizar al cliente sobre su pedido.
- ACCIÓN: Editar datos del cliente o eliminar cliente, despues de relaizar su envio. 
------------------------------------------------------------------------------------------------------------------------------------------------
## Base de Datos MySQL (smss_bs):
1. Se realizó una base de datos con el nombre de smss_bs.
2. Tablas:
- tbl_customers: Administra toda aquella informacion al cliente, mediante su registro, tambien administra el USUARIO Y CONTRASEÑA del Administrador.  
- tbl_ nombers: Nombres de los productos que hemos subido a la venta.
- tbl_ orders: Ordenes de los clientes.
- tbl_products: Los ID de los prodcutos que hemos subido a la venta 

--------------------------------------------------


## Localización del proyecto Github: 