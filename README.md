# integration-projects
Spring integration project 




# Description 
Collections of project related to Enterprise integration 


# Stack 
+ Spring framework - Spring data(JPA - Cassandra - Redis)
+ Database : PostgreSQL, Cassandra 
+ Caching : Redis - Spring session - Spring websocket 
+ Message broker : RabbitMQ
+ Apache maven (Surefire and Failsafe plugins)
+ Test : JUnit, Mockito and TestContainers (spin up Docker containers for Integration Tests)





# Features 
+ Feature 1 : Real time Chat application 
    + Create new chat room 
    + User join the chat room 
    + Open a new incognito window and create another account 
    + Sign in with this another account 
    + User join the chat room 
    + User send message 
    + User open other browser window and see the messages coming 
    + Click the username to send private message 


+ Feature 2 : Spark streaming web logs 
    + Stream web logs 
    + Apache Kafka 







+ Feature 3 :



# Run project 
+ Real time chat application 
    + Run with Docker compose : `docker-compose -f docker-compose/dependencies.yml up`
    + Run Spring boot application : `mvn spring-boot:run`







