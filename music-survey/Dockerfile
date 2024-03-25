FROM eclipse-temurin:17-jdk-alpine
VOLUME /tmp
COPY *.jar app.jar
EXPOSE 8070
ENTRYPOINT ["java", "-Dspring.profiles.active=docker", "-jar", "/app.jar"]