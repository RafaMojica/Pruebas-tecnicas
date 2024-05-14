<h2 align="center">
    <p>Prueba Tecnica Full Stack Developer</p>
    <p>Junior Advanced</p>
</h2>

<div align="center">
    <img src="https://img.shields.io/badge/Nextjs-000?logo=nextdotjs&logoColor=fff" alt="technology Next"/>
    <img src="https://img.shields.io/badge/React-149ECA?logo=React&logoColor=fff" alt="technology React"/>
    <img src="https://img.shields.io/badge/TypeScript-007EC6?logo=TypeScript&logoColor=fff" alt="technology TypeScript"/>
    <img src="https://img.shields.io/badge/Firebase-F5822C?logo=Firebase&logoColor=fff" alt="technology Firebase"/>
</div>

### Objetivo

Realiza una aplicacion que permita a los usuarios registrados, iniciar sesion y crear nots que puedean ser compartidas y editadas por otros usuarios.

### Requisitos

Libertad creativa de realizar el ejercicio como mejor te parezca, asi como agregar librerias que deseas, sin olvidar el uso de las tecnologias a continuacion siendo.

- Nextjs | React
- Typescript
- Material UI
- Firebase (firestore)
- React Hook Form
- Yup

## Funcionalidades

La aplicacion debe constar con al menos módulos

### 1. Paginacion de inicio de sesion y registro

- Los usuarios deben poder registrarse e iniciar sesion utilizando Firebase Authentication.
- Debe haber una página de registro donde los usuarios puedan crear una cuenta proporcionando su direccion de correo electronico y contraseña.
- Debe haber una pagina de inicio de sesion donde los usuarios puedan iniciar sesión utilizando su dirección de correo electrónico y contraseña

### 2. Pantalla principal de notas

- Después de iniciar sesión, los usuarios deben ser redirigidos a una pantalla principal que muestra todas las notas disponibles.
- Debe haber una forma de crear nuevas notas
- Las notas deben tener un titulo y un contenido editable.

### 3. Compartir notas

- Los usuarios deben poder compartir notas con otros usuarios. Esto puede hacerse utilizando un sistema de invitacion o compartiendo un enlace unico de la nota.

### 4. Edición coolaborativa de notas:

- Los usuarios que tengan acceso a una nota compartida deben poder editar su contenido en tiempo real.
- los cambios realizados en la nota deben reflejarse en tiempo real para todos los usuarios que tengan acceso a a la nota

### 5. Roles de usuario:

La aplicacion debe tener diferentes roles de usuario con diferentes niveles de acceso y permisos.

- **Administrador**: Tiene acceso completo a todas las funcionalidades de la aplicacion, incluyendo la gestion de usuarios, lacreacion, la edicion y eliminacion de notas, asi como la capacidad de asignar roles o otros usuarios
- **Editor**: Puede crear, editar y eliminar notas, pero no tiene acceso a las funciones de administracion de usuarios.
- **Usuario regular**: Puede ver y editar las notas compartidas a las que ha sido invitado, pero no puede crear no eliminar notas.

## Criterios de evaluación

- Se valora las buenas practicas y cretividad
