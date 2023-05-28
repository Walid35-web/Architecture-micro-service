# Architecture-micro-service
Practical activity 5: Implementing a microservice architecture
Objective:  
The creation of an application based on a micro-service architecture to manage invoices containing products belonging to a customer.
1. Create the Customer-service microservice
      - Create Customer Entity
      - Create the CustomerRepository interface based on Spring Data 
      - Deploy the microservice's Restful API using Spring Data Rest
      - Test the microservice
2. Create the Inventory-service microservice
      - Create the Product entity
      - Create the ProductRepository interface based on Spring Data
      - Deploy the microservice's Restful API using Spring Data Rest
      - Test the microservice
3. Create the Gateway service using Spring Cloud Gateway
      - Test the Service proxy using a Static configuration based on the application.yml file
      - Test the Service proxy using a Static configuration based on a Java configuration
4. Create the Registry Service directory based on NetFlix Eureka Server
5. Test the proxy using a dynamic Route Management configuration to the micro-services registered in the Eureka Server directory
6. Create Billing-Service using Open Feign to communicate with Customer-service and Inventory-service 7. Create an Angular client to display an invoice
7. Create an Angular client to display an invoice
