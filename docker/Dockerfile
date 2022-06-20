FROM alpine:latest
ADD target/helloworld-1.1.jar C:\Users\Shir Hen\Workspace\shir-training-repo\
RUN apk --update add openjdk8-jre
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "HelloWorld"]
