FROM openjdk:13.0-jdk-slim

ENV HELLO_MESSAGE: Zdarova!
RUN ls
COPY target/*.jar /application.jar

ENTRYPOINT ["java", "-jar", "/application.jar", "--spring.profiles.active=prod "]