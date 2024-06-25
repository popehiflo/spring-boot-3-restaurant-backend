# Spring Boot 3 - Restaurant:  Restaurant - backend 🥗
**Proyecto Web Fullstack**  
*Gestionar la información básica de Productos, Facturas, Clientes, Usuarios, Perfiles, etc.*  
`H2`, `PostgreSQL`, `JPA`, `Hibernate`, `Spring Boot`, `Spring Data JPA`, `Spring MVC`, `Spring Security`,
`JWT`, `JUnit`, `Mockito`, `HTML`, `CSS`, `JS`, `Bootstrap`.

## Backend Java 🛠️
*API Rest usando Java con Spring Boot 3.3.1 y base de datos H2/PostgreSQL. Uso de JPA con Hibernate para la persistencia de datos. También tiene validación de datos, manejo de excepciones, uso adecuado del protocolo HTTP en estándar REST y mucho más*
* [H2](https://www.h2database.com/html/main.html) - Base de Datos relacionales hecho con Java SQL
* [PostgreSQL 15](https://dev.mysql.com/downloads/mysql/) - RDBMS de código abierto
* [Java 17](https://www.oracle.com/java/technologies/downloads/#java17) - Java SE Development Kit 17
* [Spring](https://spring.io/) - El framework web mas usado
    * [Spring Boot]()
    * [Spring Data JPA]()
    * [Spring MVC]()
    * [Spring Security]()
* [Maven](https://maven.apache.org/) - Herramienta de gestión de dependencias

## Ejecutando localmente 🚀
Esta es una aplicación [Spring Boot](https://spring.io/guides/gs/spring-boot/) construida usando [Maven](https://maven.apache.org/). Se puede compilar y ejecutar desde la línea de comandos:
```
... despues de clonar el repositorio
cd spring-boot-3-vanillajs-clinica-web-app
.\mvnw spring-boot:run
``` 
Luego navegar hacia `http://localhost:8080/`  
Recuerda revisar el archivo [application.properties](src/main/resources/application.properties) para activar el perfil y el gestor de base de datos usara.
## Postman 📎
Colección de requests [Collection SB3-Restaurant-Backend](https://www.getpostman.com/collections/1abd828e2e340b18f803) que puedes descargar e importar en tu cliente Postman.
Se lista los distintos endpoints de la API. Tiene variables de entorno (URL_BASE, TOKEN).
## Descripción 💬
API REST que permite el CRUD o ABM de los diferentes Enums, Entidades aquí listadas:
- [Categories](src/main/java/io/github/popehiflo/restaurant/persistence/entity/Category.java): Categoría de productos.
- [Products](src/main/java/io/github/popehiflo/restaurant/persistence/entity/Product.java): Productos.
- [Invoices](src/main/java/io/github/popehiflo/restaurant/persistence/entity/Invoice.java): Facturas.
- [Customers](src/main/java/io/github/popehiflo/restaurant/persistence/entity/Customer.java): Clientes.
- [Profiles](src/main/java/io/github/popehiflo/restaurant/persistence/entity/Profile.java): Perfiles de Usuario.
- [Users](src/main/java/io/github/popehiflo/restaurant/persistence/entity/User.java): Usuarios.
- [Documents](src/main/java/io/github/popehiflo/restaurant/persistence/entity/DocumentType.java): Tipos de Documentos.

## Si encuentra un error o quiere sugerir una mejora 📧
Siéntase libre de informar problemas/errores aquí:
[Issues](https://github.com/popehiflo/spring-boot-3-restaurant-backend/issues)
## Licencia 📄
[MIT License](LICENSE)

⌨️ con ❤️ por [popehiflo](https://github.com/popehiflo) 😊