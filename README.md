Config Repository Example
------------------------------------------------------------------------------------------------------------------------

Repositorio de ejemplo para leer configuracion de microservicios desde un servicio Config Server
desarrollado con Spring Boot y Spring Cloud.

Estas configuraciones son leidas desde el proyecto "Spring Cloud Config Example":

  https://github.com/edgar-code-repository/spring-cloud-config-example

------------------------------------------------------------------------------------------------------------------------

**Configuracion para el servicio config-client-example:**

El servicio config-client-example debe correr en el puerto 5551.
Se definen las cadenas title y message para ser utilizadas desde el servicio.

```
  server.port=5551
  title=Config Client Example with Spring Boot and Spring Cloud
  message=Hello! This service gets its configuration from a Spring Cloud Config Service

```

------------------------------------------------------------------------------------------------------------------------

