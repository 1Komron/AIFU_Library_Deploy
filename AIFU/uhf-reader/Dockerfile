FROM eclipse-temurin:21-jdk

WORKDIR /app

COPY ./uhf-reader-0.0.1-SNAPSHOT.jar uhf-reader.jar

EXPOSE 8082

ENTRYPOINT ["java", "-jar", "uhf-reader.jar"]
