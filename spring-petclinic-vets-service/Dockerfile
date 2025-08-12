FROM openjdk:17-jdk

ARG JAR_FILE=target/*.jar

WORKDIR /app

COPY ${JAR_FILE} vets-service.jar

EXPOSE 8083

ENTRYPOINT ["java", "-jar", "/vets-service.jar"]
