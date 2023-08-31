FROM openjdk:8-jdk-alpine
MAINTAINER acceleritemkt
RUN mkdir -p /tmp/dw/builds
ENV PROJECT_HOME /tmp/dw/builds
COPY target/*.war $PROJECT_HOME/hello-world-war-1.0.0.war
