FROM alpine:latest
ADD helloworld-1.1.jar hello-docker-app.jar
RUN apk --update add openjdk8-jre
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "HelloWorld"]