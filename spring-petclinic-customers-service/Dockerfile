FROM openjdk:17-jdk

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} customers-service.jar

ENTRYPOINT ["java", "-jar", "/customers-service.jar"]
