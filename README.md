# Desing Document: API REST CONTACTOS 

## 1. Description
Ejemplo de una API REST para gestionar contactos en una DB utilizando FastAPI

## 2. Objetivo
Realizar un ejemplo de diseño de una API REST de tipo CRUD y su posterior codificación utilizando el framework [FastApi](https://fastapi.tiangolo.com).

## 3. Diseño de la BD
Para este ejemplo se utilizará el gestor de base de datos [SQLite3](https://www.sqlite.org/). con las sigientes tablas:

|No.|Campo|Tipo|Restricciones|Descripción|
|--|--|--|--|--|
|1|id_contactos|int|PRIMARY KEY|Llave primaria de la tabla|
|2|nombre|varchar(100)|Not Null|Nombre del contacto|
|3|primer_apellido|varchar(50)|Not Null|primer Apellido del contacto|
|4|segundo_apellido|varchar(50)|Not Null|Segundo Apellido del contacto|
|5|email|varchar(100)|Not Null|Email del contacto|
|6|telefono|varchar(13)|Not Null|Telefono del contacto|

## 3.2 Script

´´´´sql

