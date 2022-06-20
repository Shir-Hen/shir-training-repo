FROM alpine:latest
ADD target\helloworld-1.1.jar com.coveros.demo.helloworld.HelloWorld
RUN apk --update add openjdk8-jre
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "HelloWorld"]
