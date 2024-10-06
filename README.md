# bda-modulo-1-evaluacion-final-Ariana-Papantonio
bda-modulo-1-evaluacion-final-Ariana-Papantonio created by GitHub Classroom

# Proyecto de Creación de clase Tienda Online de Veterinaria

Este proyecto consiste en un sistema para gestionar una tienda online de productos de veterinaria. Permite realizar distintas gestiones como agregar clientes y productos, ver el inventario disponible, actualizar el stock, realizar compras y procesar pagos, entre otras. 


# Funcionalidades

- Agregar producto: 

Función: permite añadir productos al inventario. 
Método: agregar_producto(self, nombre_producto, precio, cantidad)


- Ver inventario: 

Función: permite ver el inventario disponible. 
Método: ver_inventario(self)


- Buscar productos:

Función: busca productos en el inventario: 
Método: buscar_producto(self,nombre)


- Actualizar stock:

Función: permite actualizar el stock de un producto
Método: actualizar_stock(self,nombre,cantidad)


- Eliminar producto: 

Función: elimina productos del inventario
Método: eliminar_producto(self,nombre)


- Calcular valor inventario: 

Función: calcula el valor total del inventario. 
Método: def calcular_valor_inventario(self)
        

- Realizar compra:

Función: permite al cliente seleccionar productos del inventario, agregar al carrito y ver el total.
Método: realizar_compras(self)


- Procesar pago:

Función: procesa el pago de la compra, calcula el cambio y muestra un mensaje de confirmación.
Método:def procesar_pago(self)


- Agregar cliente:

Función: agrega un nuevo cliente al registro de clientes. 
Método: agregar_cliente(self,nombre,email)


- Ver lista de clientes:

Función: muestra el listado completo de clientes registrados, con su nombre y correo.
Método: ver_clientes()


- Registrar compra:

Función: registra una compra para un cliente existente y la añade a su historial.
Método: registrar_compra(nombre_cliente, carrito)