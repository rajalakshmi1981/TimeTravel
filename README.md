# Time Travel Spring Boot App

This is a Time Travel REST application which stores the Travel history of the Travaller and avoids Place and Date Paradox. Also records the Travel details of the Traveller

What you'll need

    JDK 1.8 or later
    Maven 3 or later
    spring-boot 1.3.5.RELEASE

# Build 

mvn clean install

# Tests

mvn clean test

# Running App
		
mvn spring-boot:run
    
or alternatively with jar you can run from target folder 
    
java -jar TimeTravel-1.0.0.jar --server.port=9181
    
    
 The URL is /travel and the Method is POST. 
 
 Example URl: http://localhost:9181/travel
 
 Example JSON format for Request Body :
 
{
 "pgi":"1HN2HH2NNA",
 "place":"Manchester",
 "date":"2012-02-26"
} 
  
