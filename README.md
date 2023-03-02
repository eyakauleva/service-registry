
A simple sample of service registry via Spring Cloud Netflix Eureka

## Installation

1. Install Java 19 from https://www.oracle.com/java/technologies/downloads/,

2. Install Maven 3 from https://maven.apache.org/download.cgi

3. Clone this repository:
```bash
$ git clone https://github.com/eyakauleva/service-registry.git
```

4. Navigate to the project directory:
```bash
$ cd service-registry
```

5. Start the application:
```bash
$ mvn spring-boot:run
```

6. Open in browser http://localhost:8761/

## About

A service registry is a database populated with information on how to dispatch requests to microservice instances.
