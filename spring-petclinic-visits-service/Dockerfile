FROM openjdk:17-jdk

ARG JAR_FILE=target/*.jar

WORKDIR /app

COPY ${JAR_FILE} visits-service.jar

EXPOSE 8084

ENTRYPOINT ["java", "-jar", "/visits-service.jar"]
