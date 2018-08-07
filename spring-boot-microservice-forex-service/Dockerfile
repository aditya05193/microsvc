FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD target/spring-boot-microservice-forex-service-0.0.1-SNAPSHOT.jar App.jar
EXPOSE 8080
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /App.jar" ]