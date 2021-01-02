FROM openjdk:11
WORKDIR .
RUN pwd
USER root
COPY HelloWorldJava/build/libs/HelloWorldJava-0.0.1-SNAPSHOT.jar /app.jar
ENTRYPOINT ["java","-jar", "/app.jar"]
