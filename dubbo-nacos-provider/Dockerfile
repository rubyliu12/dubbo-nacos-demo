FROM openjdk:8-jdk-alpine

MAINTAINER sky.huang@zenlayer.com

ARG JAR_FILE

ADD target/${JAR_FILE} app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
