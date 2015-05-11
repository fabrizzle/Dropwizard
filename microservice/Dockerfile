
FROM mminderbinder/java-jdk:oracle-java8
MAINTAINER Milo Minderbinder <fabrizio@consist.de>

ADD target /code
ADD hello-world.yml /code/hello-world.yml
WORKDIR /code


RUN java -jar microservice-0.0.1-SNAPSHOT.jar server hello-world.yml
CMD java -jar microservice-0.0.1-SNAPSHOT.jar server hello-world.yml

EXPOSE 8080




