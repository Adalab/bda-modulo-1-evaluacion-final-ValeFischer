# bda-modulo-1-evaluacion-final-ValeFischer
Usaremos este README para agregar información sobre el código de la TiendOline.
Nos permitirá llevar un registro de inventario, realizar compras, procesar pagos, registrar clientes y visualizar información relacionada con las ventas y clientes.

## Funcionalidades

### 1. Agregar Producto
Permite agregar un nuevo producto al inventario o actualizar la cantidad disponible si el producto ya existe.

### 2. Ver Inventario
Muestra todos los productos disponibles en el inventario, incluyendo su nombre, precio y cantidad.

### 3. Buscar Producto
Busca un producto específico en el inventario por su nombre y muestra su información si está disponible.

### 4. Actualizar Stock
Permite actualizar la cantidad disponible de un producto en el inventario.

### 5. Eliminar Producto
Permite eliminar un producto del inventario.

### 6. Calcular Valor del Inventario
Calcula el valor total del inventario en base a los precios y cantidades de los productos disponibles.

### 7. Buscar Producto con Regex
Busca productos en el inventario utilizando expresiones regulares.

### 8. Realizar Compra
Permite a los clientes agregar productos a su carrito de compra, actualizando el inventario y registrando la venta.

### 9. Procesar Pago
Calcula el cambio o indica si el pago no puede ser procesado debido a fondos insuficientes.

### 10. Agregar Cliente
Permite registrar un nuevo cliente en el sistema.

### 11. Ver Clientela
Muestra la lista de clientes registrados.

### 12. Registrar Compra
Registra una compra realizada por un cliente, actualizando las ventas totales y el historial de compras del cliente.

### 13. Ver Compras Cliente
Muestra el historial de compras de un cliente específico.

### 14. Calcular Ventas Totales
Calcula el monto total de todas las ventas realizadas.

## Uso
Para utilizar este programa, simplemente instancie la clase `TiendaOnline` y utilice los métodos proporcionados según sea necesario.

Ejemplo de uso:

```python
# Crear una instancia de la tienda
tienda = TiendaOnline()

# Agregar un producto al inventario
tienda.agregar_producto("Camiseta", 20, 50)

# Ver el inventario
tienda.ver_inventario()

# Realizar una compra
tienda.realizar_compra()

# Procesar el pago
tienda.procesar_pago()

# Registrar un cliente
tienda.agregar_cliente("Juan", "juan@example.com")
```

¡Disfruta administrando tu tienda online con este programa!
```

