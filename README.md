# Book Management System API (Reactive)

Non-blocking, reactive book management service built with Spring WebFlux and R2DBC.

## Features
- Fully reactive end-to-end request handling using Project Reactor (`Mono` / `Flux`).
- Asynchronous database access via R2DBC.
- High-throughput, non-blocking I/O suited for event-driven systems.

## Tech Stack
- Java 21 LTS
- Spring Boot (Spring WebFlux)
- R2DBC (Reactive Relational Database Connectivity)
- PostgreSQL
- Maven Wrapper

## Getting Started
```bash
./mvnw clean compile
./mvnw spring-boot:run
```
