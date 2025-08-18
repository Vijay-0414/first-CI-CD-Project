FROM openjdk:17-jdk

ARG JAR_FILE=target/*.jar

WORKDIR /app

COPY ${JAR_FILE} api-gateway.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "api-gateway.jar"]
