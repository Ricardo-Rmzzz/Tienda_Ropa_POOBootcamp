Sistema de Compras de Ropas con Programacion Orientada a Objetos (POO)
Este código simula el funcionamiento básico de una tienda de ropa mediante la aplicación de los 4 pilares de la programación orientada a objetos.
- Producto: es la clase padre que define atributos comunes para todos los productos como nombre, precio, y cantidad.
- Ropa: es la clase hija que hereda de "Producto" y añade la propiedad talla.
- Los productos camisa, pantalon, chaqueta, vestido y zapato heredan de "Ropa" y redefinen el método "mostrar_info" para mostrar información personalizada según el tipo de prenda.

Instrucciones de uso:
- Al ejecutar el programa, se mostrará en pantalla el inventario disponible de la tienda.
- Luego,se pedirá que selecciones un producto por su número y especifiques la cantidad que se desea comprar.
- Se puede agregar varios productos al carrito, siempre y cuando este diponible en stock o ingresar 0 para salir.
- Al finalizar, se mostrará un resumen de la compra, los productos seleccionados y el total a pagar por la compra realizada:

