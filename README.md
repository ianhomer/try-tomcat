# try-tomcat

Try Tomcat

# TL;DR

    mvn clean install
    
    mvn spring-boot:run -pl try-tomcat-spring
    
Visit http://localhost:8080/greetings

# With Docker

    docker-compose up -d
    
Visit http://localhost/greetings

And rebuild 

    docker-compose up -d --build
    docker-compose build --no-cache apache