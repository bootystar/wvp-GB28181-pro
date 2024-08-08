FROM eclipse-temurin:11

RUN mkdir -p /app
WORKDIR /app
COPY application-local.yml /app/application-local.yml
COPY application.yml /app/application.yml
COPY wvp.jar /app/wvp.jar

ENTRYPOINT ["java", "-jar", "/app/wvp.jar"]
