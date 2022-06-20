FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD target/helloworld-1.1.jar com.coveros.demo.helloworld.HelloWorld
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /hello-docker-app.jar" ]
