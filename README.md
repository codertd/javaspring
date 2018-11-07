# javaspring

A basic Java and Spring rest service.  Using Maven 3.6.0 to build.

# to build
mvn clean package

# to run
Application.java has the SpringBootApplication annotation, which allows direct running of the jar without Tomcat/etc.
java -jar target/gs-rest-service-0.1.0.jar

http://localhost:8080/greeting?name=Tim

