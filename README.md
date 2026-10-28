# trading-parent

# Trading Parent

Parent Maven corporativo de la plataforma.

## Objetivo

Centralizar:

- Versiones Java
- Versiones Spring
- Plugins Maven
- Dependencias comunes

## Tecnologías

- Java 21
- Spring Boot 3
- PostgreSQL
- Kafka
- Redis
- Testcontainers

## Uso

Todos los microservicios deben heredar de:

```xml
<parent>
    <groupId>com.jmtrading</groupId>
    <artifactId>trading-parent</artifactId>
    <version>1.0.0</version>
</parent>