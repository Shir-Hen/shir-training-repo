FROM alpine:latest
ADD C:\Users\Shir Hen\Workspace\helloworld\src\main\java\com\coveros\demo\helloworld C:\Users\Shir Hen\Workspace\shir-training-repo\
RUN apk --update add openjdk8-jre
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "HelloWorld"]
