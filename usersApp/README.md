# UsersApp — práctica de Ionic y Angular

Aplicación Ionic con Angular que muestra una lista de usuarios activos.

## Qué contiene

- Un modelo `User` que define los datos de cada usuario.
- Un servicio `UsersService` que simula una consulta asíncrona y filtra los usuarios activos.
- Una página `users` que muestra un indicador de carga y la lista.
- Una ruta inicial que lleva a `/users`.

Los datos son locales y de ejemplo; no se necesita una API externa.

## Ejecutar el proyecto

Se necesita Node.js, npm e Ionic CLI.

```bash
npm install
ionic serve