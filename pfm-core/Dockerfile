FROM openjdk:22-ea-21-slim-bullseye
LABEL author='Sujeet Kumar'
VOLUME /tmp
COPY target/pfm-core-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar","app.jar"]