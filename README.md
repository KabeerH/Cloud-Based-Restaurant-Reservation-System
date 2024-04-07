# Cloud-Based-Restaurant-Reservation-System

# Development Process

## System Architecture (design) used: 

For this project I decided to use a microservice architecture style approach the reason why I chose this approach is because this type of architecture can have many benefits:

- Scalability: The microservices can be scaled on an independent level based on the demand. If one of the services scales with a lot of traffic then that service will be scaled up without touching the other parts of my application
- Maintenance: These microservices are independent and loosely coupled. This allows easy maintenance with the application
- Agility: Each microservice is small and can focus on a specific function allowing for easier management
- Many aspects: In a microservice style each microservice is referred to a different aspect of the overall application: In a PHR system we can have one service responsible for the (user auth, user registration, etc (frontend)) and other for the creation, retrieving, updating and deleting records (CRUD).

## Vision Statement

`FOR` individuals `WHO` need to manage, update and cancel reservations for a restaurant system. `THE` cloud-based restaurant reservation system is a tool to achieve these tasks `THAT` allows the user to create new reservations, update pre existing reservations and delete reservations (cancel). Additionally the system allows users to register for an account before making the reservation to their desired restaurant. These features can be done via APIS. `UNLIKE` traditional restaurant reservation systems, this system asks the user to register for an account in which the user will have access to multiple restaurants. This will act like a central system in which the user can make a reservation to different restaurants, saving the user time as they don’t have to go to different websites for different restaurants. `OUR` product lets the user manage their reservations in a secure environment with the proper security measures to ensure that no sensitive data gets leaked to anyone beside them and the restaurant in which they made the reservation to. 

FORMAT USED: (Moore’s vision template)

- FOR (target customer)
- WHO (statement of the need or opportunity)
- THE (Product name) is a (product category)
- THAT (key benefit, compelling reason to buy)
- UNLIKE (primary competitive alternative)
- OUR PRODUCT (statement of primary differentiation

## Personas

Persona one:  Sam Cill

- Age: 45
- Occupation: Business man 
- Currently needs: since Sam is a busy man, he doesn’t have time to search for multiple restaurants to choose a booking 
- What the restaurant reservation system does for them: the reservation system allows Sam to search for different restaurants from one central website. Saving him time and effort.

Persona two:  Sheila Shoon, Housewife (children two)
- Age: 45
- Occupation: Housewife 
- Currently needs: this household books for multiple people every week at least one time making them a frequent outside eater. They want the system to apply corresponding promotions and coupons with applicable. 
- What the restaurant reservation system does for them: the system automatically applies coupons and discounts when they book for the reservation so when they arrive at the restaurant they will get a discount. 

Persona three: Mike Loop
- Age: 30
- Occupation: Restaurant Manager 
- Currently needs: A way to manage incoming restaurant reservations in a fast and effective way with a easy to use user interface for optimal use
- What the restaurant reservation system does for them:  the system allows this user to manage the current reservations by allowing them to update, or cancel (remove) the current reservations that have been made in the system.

## Scenarios and user stories:

- `Name`: Sam Cill
- Scenario: While at work Sam realises that he forgot to book for a reservation at a restaurant. He doesn’t have time to go to multiple restaurant websites to see which one is optimal. 
- User Story: As Sam a busy business man, I want to search for different restaurants from one place so I can save time and effort

- `Name`: Sheila Shoon
- Scenario: It’s Thursday morning and Sheila plans to go to a restaurant with her two kids tomorrow but wants to get the best deals for her order, she wants all available coupons to be applied to her reservation so when she goes they are ready. 
- User Story: As Sheila A housewife, I want to have available coupons applied to my reservation so when I go to the restaurant those coupons automatically apply to my checkout.

- `Name`: Mike Loop
- Scenario: When Mike arrives to work, his staff complains of not having an automatic system in place to manage incoming reservations, and to edit user information. Incoming reservations sometimes get messed up due to this system not being in place.
- User Story: As Mike a restaurant manager, I want incoming reservations to be managed by a system so it lighten’s the staff workload


