# Getting Started with Spring-boot
## RESTful services

## Building and Executing the Application

There are two ways to proceed:

1. You can Build and run the application from the command line with Gradle or Maven.
> mvn spring-boot:run

2. You can build a single executable JAR file that contains all the necessary dependencies, classes, and resources, and run that
> mvn clean package

Then you can run the JAR file:
> java -jar target/<service>-<version>.jar 
  
Example:
> java -jar target/rest-service-0.1.0.jar

The service name and version is the one which we would mention in the POM.xml file
