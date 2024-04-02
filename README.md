# Cloud-Based-Restaurant-Reservation-System

# Development Process

## System Architecture (design) used: 

For this project I decided to use a microservice architecture style approach the reason why I chose this approach is because this type of architecture can have many benefits:

- Scalability: The microservices can be scaled on an independent level based on the demand. If one of the services scales with a lot of traffic then that service will be scaled up without touching the other parts of my application
- Maintenance: These microservices are independent and loosely coupled. This allows easy maintenance with the application
- Agility: Each microservice is small and can focus on a specific function allowing for easier management
- Many aspects: In a microservice style each microservice is referred to a different aspect of the overall application: In a PHR system we can have one service responsible for the (user auth, user registration, etc (frontend)) and other for the creation, retrieving, updating and deleting records (CRUD).

## Vision Statement

`FOR` individuals `WHO` need to manage, update and cancel reservations for a restaurant system.This cloud-based restaurant reservation system is a tool to achieve these tasks `THAT` allows the user to create new reservations, update pre existing reservations and delete reservations (cancel). Additionally the system allows users to register for an account before making the reservation to their desired restaurant. These features can be done via APIS. `UNLIKE` traditional restaurant reservation systems, this system asks the user to register for an account in which the user will have access to multiple restaurants. This will act like a central system in which the user can make a reservation to different restaurants, saving the user time as they don’t have to go to different websites for different restaurants. `OUR` product lets the user manage their reservations in a secure environment with the proper security measures to ensure that no sensitive data gets leaked to anyone beside them and the restaurant in which they made the reservation to. 

FORMAT USED: (Moore’s vision template)

- FOR (target customer)
- WHO (statement of the need or opportunity)
- THE (Product name) is a (product category)
- THAT (key benefit, compelling reason to buy)
- UNLIKE (primary competitive alternative)
- OUR PRODUCT (statement of primary differentiation
