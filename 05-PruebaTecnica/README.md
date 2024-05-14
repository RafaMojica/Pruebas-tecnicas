<h2 align="center">
    <p>Prueba Tecnica Full Stack Developer</p>
    <p>Trainee</p>
</h2>

<div align="center">
    <img src="https://img.shields.io/badge/React-149ECA?logo=React&logoColor=fff" alt="technology React"/>
    <img src="https://img.shields.io/badge/Node-20AA76?logo=Nodedotjs&logoColor=fff" alt="technology Nodejs"/>
    <img src="https://img.shields.io/badge/TypeScript-007EC6?logo=TypeScript&logoColor=fff" alt="technology TypeScript"/>
</div>

### Objetivo

Esta prueba es un desarrollo tipo **Live Coding**, puedes consultar informacion en las diferentes documentaciones oficial pero no podras copiar y pegar codigo ya realizado en plataformar como stack overflow entre otras, no olvides desactivar Github Copilot o cualquir inteligencia artificial similar.

### Requisitos

- Tener instalado Nodejs (v16.x.x o superior). Tener instalado npm.

- El código debe ser enteramente desarrollado en Typescript.

- Para cada ejercicio tendras una duracción maxima de 40 minutos

- Para la prueba es necesario realizar lo que dicta el enunciado, aunque se pueden agregar características no mencionadas (manejo de errores, repositorio de datos, validaciones, etc.).

- Dar importancia a la funcionalidad y usabilidad, más que al diseño visual.

- Se pueden asumir los aspectos que no aclare el enunciado, y realizar aclaraciones personales en caso de ser necesario.

## Ejercicio 1. Añadir y eliminar elementos de una lista (React)

### Enunciado

Crear una app en React que implemente un campo de texto y botón para añadir un elemento. Cuando se hace click en el botón, el texto en el campo de entrada debe agregarse a continuación en una lista de elementos. Además, cada vez que se hace click en cualquier elemento de la lista, debe eliminarse de la lista.

## Ejercicio 2. API REST (Nodejs)

### Enunciado

Crear una API REST en Node.js que gestione Libros y Autores. Se deben crear los endpoints mencionados mas adelante. Se puede usar almacenamiento en memoria o el sistema gestor de bases de datos de su preferencia.

### Entidades

Debe existir una relación del tipo Many-to-Many entre los libros y los autores

- Entidad Libro (book):

  - **id:** number
  - **title:** string
  - **chapters:** number. Representa la cantidad de capítulos.
  - **pages:** number. Representa la cantidad de páginas.

- Entidad Autor (author):
  - **id:** number
  - **name:** string

### Endpoints

- **Nuevo Libro:** Creará un nuevo libro, aportando todos sus datos incluidos los autores.
- **Obtener todos los libros:** Deberá devolver un listado de libros con sus autores.
- **Crear un autor:** Creará un nuevo autor
- **Obtener todos los autores:** Deberá devolver un listado de todos los autores con los libros que tengan.
- **Obtener Promedio de Páginas por Capítulo:** Obtener el dato de una instancia de Libro ya creada. Se debe devolver el id del libro consultado y un promedio de páginas por capítulo. Ambos en formato cadena, y con 2 decimales para el promedio.
