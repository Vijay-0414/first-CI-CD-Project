FROM openjdk:17-jdk

ARG JAR_FILE=target/*.jar

WORKDIR /app

COPY ${JAR_FILE} discovery-server.jar

EXPOSE 8082

ENTRYPOINT ["java", "-jar", "/discovery-server.jar"]
