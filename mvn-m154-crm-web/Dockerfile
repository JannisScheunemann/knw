FROM openjdk:8u191-jdk-alpine3.9

MAINTAINER Jannis Scheunemann "jannis.scheunemann@gibmit.ch"

EXPOSE 7070

WORKDIR /usr/local/bin

COPY ./target/mvn-m154-crm-web-0.0.1-SNAPSHOT-shaded.jar crm-web_docker.jar

CMD ["java", "-jar", "crm-web_docker.jar"]