FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/ms-eureka-0.0.1.jar
COPY ${JAR_FILE} app_ms-eureka.jar
ENTRYPOINT ["java","-jar","app_ms-eureka.jar"]