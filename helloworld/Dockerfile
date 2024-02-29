# You can change this base image to anything else
# But make sure to use the correct version of Java
FROM adoptopenjdk/openjdk11:alpine-jre

ARG artifact=/target/helloworld.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

ENTRYPOINT [ "java","-jar","app.jar"]