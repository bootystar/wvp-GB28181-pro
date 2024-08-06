FROM eclipse-temurin:11

RUN mkdir -p /app
WORKDIR /app

EXPOSE 5015
EXPOSE 5005
EXPOSE 15060/tcp
EXPOSE 15060/udp

ENTRYPOINT ["java","-agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=*:5005","-jar", "/app/wvp.jar"]
