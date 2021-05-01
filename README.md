# tsm-samples 

A collection of sample applications to demonstrate how Spring Cloud works on Kubernetes and Tanzu Service Mesh. This
application consits of two services:

* **message-service**: A Spring Boot microservice that returns a random inspirational quote
* **billboard-client**: A Spring Boot application that calls the message-service to get the random quote and displays
   a rotating banner of messages that change on a timer. The billboard-client makes a call over https
  

  