
FROM mminderbinder/java-jdk:oracle-java8
MAINTAINER Milo Minderbinder <fabrizio@consist.de>

ADD target /code
WORKDIR /code

EXPOSE 8081
EXPOSE 8080
CMD ["java -jar","microservice-0.0.1-SNAPSHOT.jar","server hello-world.yml"]




