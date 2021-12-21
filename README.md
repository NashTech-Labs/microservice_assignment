# microservice_assignment

This is the KUP Assignment for building Microservices.

Grub sells a range of exclusive products across India through online. The existing system used by the company has developed using legacy technologies. Currently, Grub Company is facing issues with their existing architecture. Major issue is the deployment time taken for monolith webservices, which is impacting other functionalities to non-available during the deployment. As a decision made by the leadership, it has decided to rewrite the system using modern technologies and architecture which solves their existing issues with deployment and development.


Architecture Diagram

# Microservices
## Customer Service
  ### Get Customer
  ### Create Customer
  
## Product Service
   ### Create Product
   ### Delete Product
   ### Edit Product
   ### Bulk Upload Product
   
## Order Service
   ### Place Order
   ### Update Order Status
   
## Payment Service
   ### Make Payment for an Order
   ### Update Payment for an Order
   
   Order Service should communicate with the Payment Service in Asynchronous way using Kafka.

API Documentation Through Swagger should exist for all the Services



