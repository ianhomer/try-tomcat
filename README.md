# try-tomcat

Try Tomcat

# TL;DR

    mvn clean install
    
    mvn spring-boot:run -pl try-tomcat-spring
    
Visit http://localhost:8080/greetings

# With Docker

    docker-compose up -d
    
Visit 

* http://localhost/greetings
* http://localhost:8001/greetings
* http://localhost:8002/greetings

# Redeployment

Full rebuild 

    mvn clean install && docker-compose up -d --build && docker-compose logs -f

Just apache configuration

    docker-compose up -d --build apache && docker-compose logs -f
