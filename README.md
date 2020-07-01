# TimeTravel Spring Boot App

This is a Time Travel REST application

What you'll need

    JDK 1.7 or later
    Maven 3 or later
    spring-boot 1.3.5.RELEASE

Build 

mvn clean install

Run
		
    mvn spring-boot:run
    
    or alternatively with jar you can run from target folder 
    
    java -jar TimeTravel-1.0.0.jar
    
    
 The URL is /travel and the Method is POST. 
 
 Example URl: http://<hostanme>:<port>/travel
 
 Example JSON format for Request Body :
 
{
 "pgi":"1HN2HH2NNA",
 "place":"Manchester",
 "date":"2012-02-26"
} 
  
