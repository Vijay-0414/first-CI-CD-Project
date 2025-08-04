FROM openjdk:17-jdk

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} visits-service.jar

ENTRYPOINT ["java", "-jar", "/visits-service.jar"]
