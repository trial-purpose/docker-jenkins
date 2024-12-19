FROM openjdk:17-jdk-slim
EXPOSE 8080
COPY target/docker-jenkins-integration.jar doc-jen.jar
ENTRYPOINT ["java", "-jar", "doc-jen.jar"]