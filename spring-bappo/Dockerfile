FROM openjdk:17-jdk-slim
ADD /build/libs/*.jar spring-bappo.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/spring-bappo.jar"]