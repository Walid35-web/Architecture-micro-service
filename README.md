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


## Part One 
1.create the customer-service microservice to manage customers
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/883e7ff2-8ef8-4590-acf6-6cb80581b96c)
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/059ae85b-6788-4e85-9b8f-ed51f6093cbc)
### Customer H2 Console :
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/eaa46714-87a3-4f8a-a15c-9e413189b765)
### Actuator : 
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/5e0a6e33-a474-47ac-841d-0a71a6b718e3)
2.create the inventory-service microservice to manage products
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/be816d2f-7224-405c-b243-201f36b81f6a)
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/8b9fd285-0b55-4081-9a37-0749abc5fab8)
### Product H2 Console :
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/e702622e-80d3-425a-9f9b-8274d2c57f4e)
### Customers & Products with gateway : 
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/00de5bcc-c574-4683-9f6a-bb215cd27f75)
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/b74cee17-2f1f-4df7-bcdf-268a66ea9b3c)
### Eureka after enabling Discovery Service :
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/ac2fb8e6-f6f4-4736-9608-ba1790911f85)
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/26d8bea1-ab09-40de-9a82-07665759ac20)
### Customers with id using the Web Service :
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/445f1ec3-3260-4a3c-93a8-9781e9c12ca9)
### Products with id using the Web Service :
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/0056f43c-e63b-496d-94f8-68cd404fa144)
## Deuxième Partie : 

### H2 Console Bill :
![WhatsApp Image 2023-05-27 at 22 29 14](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/f4bdb058-8aba-4589-a1e6-f3773b3a32c7)
### H2 Console Product Item : 
![image](https://github.com/Walid35-web/Architecture-micro-service/assets/85175578/e72fb0f8-fb1d-431f-944b-7455195b952f)
## troisieme partie:
### Produits : 



