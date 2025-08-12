FROM openjdk:17-jdk

ARG JAR_FILE=target/*.jar

WORKDIR /app

COPY ${JAR_FILE} customers-service.jar

EXPOSE 8081

ENTRYPOINT ["java", "-jar", "/customers-service.jar"]
