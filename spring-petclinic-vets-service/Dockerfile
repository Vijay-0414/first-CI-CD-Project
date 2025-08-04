FROM openjdk:17-jdk

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} vets-service.jar

ENTRYPOINT ["java", "-jar", "/vets-service.jar"]
