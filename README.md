# api-core-ejercito-statistics-eureka-microservice

Microservicio encargado de actuar como **servidor de descubrimiento** (Service Registry) para los servicios del
ecosistema **Core Ejército - Estadísticas**.  
Utiliza **Spring Cloud Netflix Eureka Server** para permitir que los microservicios se registren y descubran
dinámicamente dentro de la arquitectura distribuida.

## 📋 Características

- Registro centralizado de microservicios del dominio de estadísticas.
- Descubrimiento dinámico de instancias y balanceo de carga.
- Integración con microservicios de negocio, seguridad y persistencia.
- Panel de administración web para monitorear el estado de cada servicio.
- Configuración simple y escalable.

## 🛠 Requisitos

- **Java**: 11+
- **Spring Boot**: 2.x o superior
- **Spring Cloud Netflix Eureka Server**
- **Maven**: 3.9.4

Dependencias clave:

```xml

<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-netflix-eureka-server</artifactId>
</dependency>
```
