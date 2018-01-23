FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY gateway-spring-1.0.0-RELEASE.jar /gateway-spring-1.0.0-RELEASE.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/gateway-spring-1.0.0-RELEASE.jar"]
