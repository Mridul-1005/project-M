# Spring Boot Project Setup Instructions

This is a Spring Boot web application project using Maven.

## Project Overview

- **Language**: Java 17
- **Build Tool**: Maven
- **Framework**: Spring Boot 3.2.0
- **Web Support**: Spring Boot Web Starter

## Key Files

- `pom.xml` - Maven project configuration with Spring Boot dependencies
- `src/main/java/com/example/demo/DemoApplication.java` - Application entry point
- `src/main/java/com/example/demo/HelloController.java` - REST API controller
- `src/main/resources/application.properties` - Spring Boot configuration

## Development Commands

### Build
```bash
mvn clean install
```

### Run
```bash
mvn spring-boot:run
```

### Test
```bash
mvn test
```

### Package
```bash
mvn package
```

## Testing the Application

Once running, test the endpoints:
- http://localhost:8080/ - Main greeting
- http://localhost:8080/api/message - API message endpoint

## IDE Setup

Recommended VS Code Extensions:
- Extension Pack for Java
- Spring Boot Extension Pack

## Troubleshooting

- Ensure Java 17+ is installed: `java -version`
- Clear Maven cache: `mvn clean`
- Reload VS Code workspace after Maven changes
