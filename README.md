# Gestor de Inventario para una Empresa de Retail

## Descripción del Caso
Se ha solicitado crear un software para gestionar el inventario de productos en una empresa de retail. Este sistema debe permitir realizar operaciones básicas de gestión de productos. Las funcionalidades necesarias son:

- **Agregar un producto**: Permitir añadir productos con atributos como ID, nombre, cantidad y precio.
- **Eliminar un producto**: Eliminar un producto del inventario por su ID.
- **Modificar un producto**: Actualizar atributos como precio, cantidad o nombre de un producto existente.
- **Consultar producto por ID**: Verificar si existe un producto y, en caso afirmativo, mostrar su información.
- **Aplicar descuento a un producto**: Modificar el precio de un producto aplicando un porcentaje de descuento.
- **Calcular el valor total del inventario**: Sumar el valor de todos los productos del inventario (cantidad * precio por cada producto).

## Requisitos Adicionales
- Implementar validaciones para cada operación. Asegurarse de que las entradas sean válidas y manejar los casos en los que no se pueda realizar la operación (e.g., producto no existente al intentar eliminar o modificar).
- Crear excepciones personalizadas para manejar errores específicos, como `ProductoNoEncontradoException` o `InventarioVacioException`.
- Aplicar pruebas unitarias (PU) para validar el correcto funcionamiento de las funcionalidades, tanto para operaciones con valor de retorno (e.g., el cálculo del valor total) como para operaciones de tipo `void` que alteren la estructura de otros datos (e.g., eliminar o modificar productos).
