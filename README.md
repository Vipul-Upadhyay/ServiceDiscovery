# Service Discovery Application

This is a Spring Boot application that serves as a Eureka Server for service discovery. It allows microservices to register themselves and discover other registered services.

## Prerequisites

- Java 11 or higher
- Maven 3.6.0 or higher

## Getting Started

### Clone the repository

```sh
git clone https://github.com/your-username/service-discovery.git
cd service-discovery
```
### Build the project
```sh
mvn clean install
```
### Run the application
```sh
mvn spring-boot:run
```
### Configuration
You can configure the Eureka Server by modifying the application.yml file located in the src/main/resources directory.  

### Dependencies
Spring Boot
Spring Cloud Netflix Eureka Server

### License
This project is licensed under the MIT License - see the LICENSE file for details. 
