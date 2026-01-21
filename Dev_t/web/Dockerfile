FROM eclipse-temurin:21-jdk

WORKDIR /app

COPY ./library-web-0.0.1-SNAPSHOT.jar app-web.jar

RUN apt-get update && apt-get install -y \
    libfreetype6 \
    fontconfig \
    && rm -rf /var/lib/apt/lists/*

EXPOSE 9090

ENTRYPOINT ["java", "-jar", "app-web.jar"]

