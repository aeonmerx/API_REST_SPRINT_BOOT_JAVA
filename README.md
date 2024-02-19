**API REST CON SPRINT BOOT JAVA MVC WEB**

La aplicación fue desarrollada utilizando la tecnología Java Spring Webflux, adoptando un enfoque de programación reactiva y orientada a objetos. 
Este proyecto es una aplicación Gradle desarrollada en Java utilizando Spring Webflux, una tecnología basada en programación reactiva.
El objetivo principal es exponer dos microservicios RESTful en formato JSON, implementando un método POST y un método GET. Además, se busca asegurar un código limpio y modular, utilizando programación funcional en al menos un 70%.

Requisitos
Java 9 o superior
IntelliJ IDEA (Recomendado)

Microservicios REST
La aplicación expone dos microservicios REST en formato JSON:
en las rutas :
**api/personas** y
**api/empresas**
CON LOS MÈTODOS HTTP GET, POST, PUT, DELETE
ORM HIBERNATE
Tiene un extra en las vistas del CRUD usando Thymeleaf
Las migraciones son con Flyway.
La base de datos es MYSQL
LINK DE COLECCIÒN DE POSTMAN
https://api.postman.com/collections/21092219-6fbf54f7-ba0b-4710-9871-05b60d0067d6?access_key=PMAT-01HQ14CQ33E69Y5TSNV9G2VWJ9


**HISTORIAS DE USUARIO**

- Historia de Usuario:Creación de Entradas para Personas

Como usuario desarrollador, quiero poder crear entradas para personas a través de un servicio RESTful utilizando la aplicación Spring Webflux. Esto me permitirá almacenar información relevante en la base de datos y garantizar la integridad de los datos.

**Criterios de Aceptación:**

- Como usuario desarrollador, quiero exponer un endpoint POST con la ruta /api/personas para crear nuevas entradas para personas.

- Como usuario desarrollador, quiero definir un formato JSON para la entrada con al menos tres campos (campo1, campo2, campo3) que representarán la información relevante de la persona.

- Como usuario desarrollador, quiero recibir un mensaje de confirmación indicando que la entrada para la persona ha sido creada exitosamente.

- Como usuario desarrollador, quiero asegurar la validez de los datos mediante al menos tres validaciones que se ejecutarán durante el proceso de creación.

- Historia de Usuario: Obtener Información de Personas por Parámetro

- Como usuario desarrollador, necesito poder obtener información sobre una persona específica mediante un servicio RESTful utilizando la aplicación Spring Webflux. Esto me permitirá acceder y mostrar datos específicos de una persona almacenados en la base de datos.

**Criterios de Aceptación:**

- Como usuario desarrollador, quiero exponer un endpoint GET con la ruta /api/personas/{parametro} para obtener información sobre una persona específica.

- Como usuario desarrollador, quiero definir un parámetro único ({parametro}) que se utilizará como identificador para recuperar la información de la persona.

- Como usuario desarrollador, quiero recibir la información de la persona en formato JSON, incluyendo cuatro campos (nombres, apellidos, telefono, correo).

- Como usuario desarrollador, quiero garantizar la existencia del parámetro y manejar adecuadamente los casos en los que no se encuentre información.


