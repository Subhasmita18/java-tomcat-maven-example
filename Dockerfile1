FROM java:8-jdk-alpine
COPY ./target/dependency/webapp-runner.jar /usr/app/
COPY ./target/java-tomcat-maven-example.war /usr/app/
WORKDIR /usr/app
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "webapp-runner.jar","java-tomcat-maven-example.war"]
