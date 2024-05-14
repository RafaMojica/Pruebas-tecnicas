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

Esta prueba es un desarrollo tipo `Live Coding`, puedes consultar informacion en las diferentes documentaciones oficial pero no podras copiar y pegar codigo ya realizado en plataformar como stack overflow entre otras, no olvides desactivar Github Copilot o cualquir inteligencia artificial similar.

### Requisitos

- **Fontend**

  - React

- **Backend**

  - Node/ Express utilizando TypeScript (preferiblemente) o JavaScript
  - Un ORM como sequelize o similar para manejar la DB

- **Storage**
  - Cualquier DB de tipo relacional

## Propuesta

Utilizando la API de Spotify, se deben listar todos los álbumes (con sus respectivas imágenes) de un artista en particular ordenados descendentemente por popularidad.

El nombre del artista debe ser proporcionado por el usuario desde el frontend. En caso de que exista más de un artista con ese nombre se debe seleccionar el primer artista de la lista.

Por cada solicitud, el backend debe almacenar en la DB la IP del usuario, la fecha de la solicitud y el nombre del artista.
​
El frontend no debe comunicarse directamente con la API de Spotify. Debe comunicarse con el backend y desde este es que se debe realizar la request a la API de Spotify

El diseño debe ser responsive.

### Notas

- Se valorá el buen uso de git (commits, branches, etc)
- Se puede utilizar librerias extra, tanto de frontend como de backend
