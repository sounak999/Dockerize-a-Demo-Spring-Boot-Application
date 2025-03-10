FROM eclipse-temurin:17

LABEL maintainer = "sounaksaha333@gmail.com"

WORKDIR /app

COPY target/demo-0.0.1-SNAPSHOT.jar app/springboot-docker-demo.jar

ENTRYPOINT["java", "-jar", "springboot-docker-demo.jar"]

