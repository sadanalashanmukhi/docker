FROM java:17-jdk-alpine
COPY target/helloworld-0.0.1-SNAPSHOT.jar /usr/app
WORKDIR usr/app
RUN sh -c 'java -jar helloworld-0.0.1-SNAPSHOT.jar'
