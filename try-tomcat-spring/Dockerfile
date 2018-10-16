FROM openjdk:10.0.2-jdk
WORKDIR /
ADD target/try-tomcat-spring-1.0.0-SNAPSHOT-exec.jar try-tomcat-spring-exec.jar
EXPOSE 8009 8080
CMD java -jar try-tomcat-spring-exec.jar