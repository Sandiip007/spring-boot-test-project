# Spring Boot REST API Test Project

This is a minimal Spring Boot REST API project with one endpoint and a controller test.

## Project structure

- `src/main/java/com/example/demo/DemoApplication.java` - Spring Boot app entry point
- `src/main/java/com/example/demo/controller/GreetingController.java` - sample REST controller
- `src/test/java/com/example/demo/controller/GreetingControllerTest.java` - MVC test for the endpoint

## Run locally

1. Install Java 17+
2. Install Maven
3. From the project root, run:

```bash
mvn spring-boot:run
```

Then open:

```text
http://localhost:8080/api/hello
```

Expected response:

```json
{"message":"Hello from Spring Boot!"}
```

## Run tests

```bash
mvn test
```
