<h2 align="center">
    <p>Prueba Tecnica Full Stack Developer</p>
    <p>Junior</p>
</h2>

<div align="center">
    <img src="https://img.shields.io/badge/Nextjs-000?logo=nextdotjs&logoColor=fff" alt="technology Next"/>
    <img src="https://img.shields.io/badge/Node-20AA76?logo=Nodedotjs&logoColor=fff" alt="technology Nodejs"/>
    <img src="https://img.shields.io/badge/TypeScript-007EC6?logo=TypeScript&logoColor=fff" alt="technology TypeScript"/>
    <img src="https://img.shields.io/badge/Tailwind-37B6D4?logo=tailwindcss&logoColor=fff" alt="technology tailwindcss"/>
</div>

### Objetivo

Este proyecto está diseñado para poner a prueba su conocimiento de tecnologías backend y frontend, evaluando su capacidad para crear API’s e interfaces de usuario prestando atención a los detalles. También es importante la aplicación de buenas prácticas de desarrollo.

### Consideraciones

UX/UI no será tomado en cuenta para evaluar este desafío, pero se espera una mínima implementación usando tailwind.

## Funcionalidades de backend

Debe implementar una API (REST o Graphql) usando el framework Expressjs (Typescript opcional). La API debe permitir:

- Crear, Leer y Actualizar Usuarios con los siguientes campos

  - id
  - Nombres
  - Apellidos
  - Dirección
  - Historial de gasto

- Crear, Leer, Actualizar y borrar productos.
  - Solo ciertos usuarios con permisos especiales pueden realizar estas acciones.
  - Los productos deben tener los siguientes campos:
    - id
    - Nombre
    - Precio
    - Stock
    - imagen
- Añadir y quitar productos de un carrito de compras.
- En caso de que dos usuarios compren un mismo producto con stock unitario. La API debe enviar la lista de id’s de los productos que deben eliminarse de la lista del carrito de compras del usuario que perdió la compra del producto (estos id’s se usaran para manejar el error en el frontend).

## Funcionalidades de Frontend

Debe crear una aplicación usando Nextjs, ReactQuery, Tailwind y Typescript. La aplicación debe implementar las siguientes páginas:

- Login / Registro de usuario
- Barra de navegación
- Productos en venta
- Carrito de compras
  - El carrito de compras debe tener un botón “Comprar” que al ser pulsado actualice el historial de gastos del usuario y a la vez haga una reducción en el inventario de los productos comprados
  - Si el stock de un producto se encuentra en cero al momento de hacer la compra, se debe mostrar un error de compra por stock al usuario. Además, el o los productos fuera de stock deben ser removidos de la lista de productos en venta y del carrito de compras del usuario.
- Perfil de usuario donde el mismo pueda actualizar excepto el historial de compras. (esta página será accesible solo para usuarios autenticados)
- Creación, actualización y eliminación de products. (esta página será accesible solo para usuarios con permisos especiales)
- Se debe hacer uso de ReactQuery para hacer las peticiones al servidor implementado.
- Debe existir validación de campos y un manejo correcto de errores enviados por el servidor.
