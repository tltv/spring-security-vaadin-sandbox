spring-security-vaadin-sandbox
==============================

Sandbox Vaadin 7 project to play with Spring Security


## Building and running

* git clone <url of the Gantt repository>
* mvn clean install
* mvn jetty:run

Navigate to http://localhost:8080/ui -> Spring Security should redirect to /login with username and password prompt. 
Login with Username "user" and password "password" to get into the /ui Vaadin app.
