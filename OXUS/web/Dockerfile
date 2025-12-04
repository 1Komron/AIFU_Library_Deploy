FROM openjdk:21-jdk-slim

WORKDIR /app

COPY target/library-web-0.0.1-SNAPSHOT.jar app-web.jar

EXPOSE 8090

ENTRYPOINT ["java", "-jar", "app-web.jar"]
