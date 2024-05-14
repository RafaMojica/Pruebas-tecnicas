<h2 align="center">
    <p>Technical Test Backend Developer</p>
    <p>Trainee</p>
</h2>

<div align="center">
    <img src="https://img.shields.io/badge/Node-20AA76?logo=Nodedotjs&logoColor=fff" alt="technology Nodejs"/>
    <img src="https://img.shields.io/badge/MongoDB-2B694A?logo=MongoDB&logoColor=fff" alt="technology MongoDB"/>
    <img src="https://img.shields.io/badge/PostgreSQL-1D4B9A?logo=Postgresql&logoColor=fff" alt="technology Postgresql"/>
    <img src="https://img.shields.io/badge/TypeScript-007EC6?logo=TypeScript&logoColor=fff" alt="technology TypeScript"/>
    <img src="https://img.shields.io/badge/JavaScript-EFD838?logo=JavaScript&logoColor=fff" alt="technology JavaScript"/>
</div>

### Objective

This challenge aims to evaluate basic skills in Node.js development, and a bit of data/entity modeling. The idea is to build an HTTP REST API.

## Functionality

The API has to fulfill the following conditions:

- Endpoints for authentication using JWT.<br/>
  Include an endpoint for refreshing the JWT access token.
- Endpoint for retrieving movies.<br/>
  It should be allowed to filter and sort by some field.
- Endpoint for retrieving the information (director included) of a specific episode of a TV Show
- Endpoint for adding a new object (it could be for any entity you like).

### Model & API

Entities to consider:

- Movie<br/>
  Has many actors, but one director.
- TV Show<br/>
  Has many actors. It also has seasons and episodes inside each of one.
- Actor<br/>
  Can be on different movies and tv shows.
- Director<br/>
  Can direct many movies and specific episodes of tv shows.

Use your common sense (or imagination) to define the descriptive attributes/properties of each entity. For example, name or genre.

## Tech Requirements

These are the following conditions for the development:

- The code should be using **Node.js 16 or superior**.
- The code could be written in **Javascript or Typescript**.
- All the code and comments should be written in **english**.
- Use a **proper naming conventions** and standards when defining the structure of the project and the name of variables, functions, etc.
- Use a **proper structure** to define the different path for the API endpoints
- The use of ESLint or other linter is optional.
- The database could be **relational or NoSQL**, it's up to you. The use of ORM is optional too.
- The database doesn't need to be presented. But the model should be represented in some way. It could be in the form of ORM configuration or at least a minimal documentation or example of some of the entities.
- Add some minimal documentation (in the form of a README file) describing how to run the project and if there is any requirement or consideration to do so.
