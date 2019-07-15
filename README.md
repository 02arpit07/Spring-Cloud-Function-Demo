# Spring-Cloud-Function-Demo
A demo of Spring cloud function

#### How to run the demo?

 - Clone the project on local
 - Open it in an IDE as a Maven project
 - Run the application class
 - Use curl to trigger one of the `@Bean` annotated functions or the `Hello` class function
 ```$xslt
curl -H 'Content-Type: text/plain' http://localhost:8080/hello -d 'Varun'     
```