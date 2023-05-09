# Cinema App
Cinema App is Java web project is built with SOLID and OOP principles in mind. 
Unique functionality is also provided for both user and admin roles.
The application supports all CRUD operations These design choices ensure the project is flexible and maintainable.
## Content
- [Features for User](#user-features)
- [Additional features for Admin](#admin-features)
- [Technologies](#technologies)
- [Project structure](#project-structure)
- [How to start the program](#how-to-start-the-program)
- [UML Database Diagram](#uml-database-diagram)

## Features for User
- Registration: Users can register for an account on the platform.
- Get all cinema halls: Users can view a list of all the cinema halls available on the platform.
- Get all movies: Users can view a list of all the movies available on the platform.
- Get all movie sessions: Users can view a list of all the movie sessions available on the platform.
- Get my orders: Users can view a list of all the orders they have placed on the platform.
- Complete my orders: Users can complete their orders by paying for the tickets.
- Add movie session to shopping cart: Users can add a movie session to their shopping cart for purchase.
- Get my shopping carts: Users can view their shopping cart and the items they have added to it.

## Additional features for Admin
- Add cinema halls: Admins can add new cinema halls to the platform.
- Add movies: Admins can add new movies to the platform.
- Add, Update, Delete movie sessions: Admins can add, update, and delete movie sessions on the platform.
- Get all users: Admins can view a list of all the users registered on the platform.

## Technologies
- JDK 17 
- Maven 3.1.1
- Spring security 5.6.10
- Spring Web 5.6.10
- Spring 5.3.20
- Hibernate 5.6.14.Final
- Tomcat 9.0.73
- MySQL

## Project structure
- src/main/java - Contains the Java source code for the project, organized according to a layered architecture.
  - controller - Contains the controllers that handle incoming HTTP requests and delegate to the appropriate service layer.
  - dao - Contains the data access objects that handle interactions with the database.
  - model - Contains the domain model objects representing the entities in the system.
  - service - Contains the business logic and serves as an intermediary between the controller and dao layers.
- src/main/resources - Contains the application configuration files.
- pom.xml - The Maven project configuration file.

## How to start the program
- 1) Ensure that you have JDK 17 , Maven, and MySQL 8.0.22 installed on your system.
- 2) Clone the project from GitHub
- 3) Update the database configuration in db.properties with your own MySQL credentials.
- 4) Run the Maven command mvn clean package to make sure everything is fine.
- 5) Configure TomCat for this project
- 6) Access the application at http://localhost:8080 in your web browser.
- 7) You can use password and login from DataInitializer

## UML Database Diagram

![pic](images/Diagram.png)
