FROM eclipse-temurin:21-jdk

WORKDIR /app

COPY ./migration-service-0.0.1-SNAPSHOT.jar app-migration.jar

EXPOSE 9093

ENTRYPOINT ["java", "-jar", "app-migration.jar"]

