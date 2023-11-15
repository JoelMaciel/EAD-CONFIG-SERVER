# MICROSERVICE CONFIG SERVER

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/JoelMaciel/Product-Catalog/blob/readm/LICENCE)

## About the Project

**Spring Cloud Config provides server-side and client-side support 
for externalized configuration in a distributed system. With the 
Config Server, you have a central place to manage external properties
for applications across all environments. The concepts on both client 
and server map identically to the Spring Environment and 
PropertySource abstractions, so they fit very well with Spring 
applications but can be used with any application running in any 
language**

> **Note:**  **Spring Cloud Config Server provides an HTTP
resource-based API for external configuration 
(name-value pairs or equivalent YAML content).
The server is embeddable in a Spring Boot 
application, by using the @EnableConfigServer 
annotation.**


## Technology Stack

- **Core:** Java with Spring Framework
- **Service Discovery:** Eureka
- API Gateway
- **Message Broker:** RabbitMQ

## Getting Started

### Prerequisites

- Java Development Kit (JDK 11)

### Clone the Repository
git clone https://github.com/JoelMaciel/EAD-CONFIG-SERVER.git

### Navigate to the Project Directory
cd EAD-CONFIG-SERVER
### Build the Project using Maven
./mvnw clean install
### Run the Application
./mvnw spring-boot:run

## Request Images

#### Microservice Course registered in Service Discovery Eureka and queued in RabbitMQ




