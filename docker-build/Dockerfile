#FROM ubuntu
#RUN apt update
#RUN apt install openjdk-8-jdk -y tomcat9 -y
#COPY addressbook-2.0.war /webapps
FROM bitnami/tomcat
COPY addressbook.war /app
