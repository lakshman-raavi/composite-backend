# Composite Backend

Spring Boot backend for the S3 + CloudFront + EC2 demonstration.

## Run
mvn spring-boot:run

## Build
mvn clean package

## Run JAR
java -jar target/composite-backend-0.0.1-SNAPSHOT.jar

## API
GET /api/hello
GET /api/health
GET /actuator/health

Server port: 8080
