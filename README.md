# eureka-service

Service registry for the Food on Wheels application, built with Spring Cloud Netflix Eureka.

## Purpose

Each microservice (restaurant listing, menu directory, user details, order) registers
with this server on startup. Services find each other through the registry by name
instead of hardcoded host addresses.

## Tech

- Java 17
- Spring Boot
- Spring Cloud Netflix Eureka Server

## Run locally

1. Clone the repo.
2. Run `./mvnw spring-boot:run`.
3. Open the Eureka dashboard at http://localhost:8761 to see registered services.

## Part of

[food-on-wheels-org/README](https://github.com/food-on-wheels-org/README), the overview of the full application.
