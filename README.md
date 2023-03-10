# **Cinema-App**
___
## Project description:
The main objective of this project is to explore and demonstrate
various features of JEE/Spring. The application shows a simple movie 
database and will offer many demo functionalities like inserting and updating movie 
information, creating an order,
registering a user, searching the database by various parameters.

___
### List of implemented features.

* Listing movies from database
* Entering and updating movies
* User registration
* Web service for movie informations
* Get user by email
* View all available cinema halls movies, movie sessions, orders

 For users with a USER role only:
  * add movie sessions to user's shopping cart;
  * view shopping cart by user's ID;
  * complete order.

 For users with an ADMIN role only:

  * add movie, movie session, cinema hall.

___
### The following technologies were used in the project
* Java 11; [downland](https://www.oracle.com/cis/java/technologies/javase/jdk11-archive-downloads.html)
* Git; [downland](https://git-scm.com/downloads)
* Apache Maven 4.0.0; [downland](https://maven.apache.org/download.cgi)
* Hibernate 5.4.15;
* Hibernate Validator 6.1.5;
* Apache Tomcat; [downland](https://tomcat.apache.org/download-90.cgi)
* MySQL 8.0.20; [downland](https://www.mysql.com/downloads/)
* JDBC;
* Javax Servlet;
* JSP;
* JSTL;
* HTML/CSS;
* Apache Maven Checkstyle Plugin 3.1.1;
* Project Lombok;
* Intellij IDEA Ultimate [downland](https://www.jetbrains.com/idea/download/#section=windows)
* MySQL Workbench [downland](https://dev.mysql.com/downloads/workbench/)
* Spring Framework, WebMVC 5.2.6;
* Spring Security 5.3.3;
* Servlet API 4.0.1;
* Jackson Databind 2.11;
* Lombok 1.18.12;

___
### How to start the program
1. Download all programs
2. Clone the project from GitHub
3. Create new project form Version Control in Intellij IDEA
4. Configure /resources/db.properties with your own URL, username, password and JDBC driver
5. Open and connect MySQL Workbench with IDEA
6. Configure Tomcat server (IMPORTANT 9 version)
7. Run the project.
   After you launch this project:
   By default, there is one user with the USER role (email = "user@i.ua", password = "user123") 
   and one with an ADMIN role (login = "admin@i.ua", password = "user123"). 
   You can change these at /cinema-app/src/main/java/com/cinema/config/DataInitializez.java
___

### This project is RESTful and MVC-based and thus has:
  * DAO layer;
  * Service layer;
  * Controllers;
  * DTOs.

___
### Model structure:
![cinema-app](https://github.com/mate-academy/hibernate-order-hw/blob/master/Hibernate_Cinema_Uml.png?raw=true)
___
### P.S.
Enjoy your life

![cinema-app](https://mag-cinema.com/image/catalog/News/2020/mammut1.jpg)
