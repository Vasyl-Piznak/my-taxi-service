# 🚖 My taxi-service 🚖
## Project description:
This is web application that supports authentication, registration and other CRUD operations.

![image](https://github.com/Vasyl-Piznak/my-taxi-service/assets/106866989/fa35627d-2e25-4680-b481-151a47ddb4c2)
 
## Project structure:
- Data access tier -> handled by DAO;
- Business logic tier -> handled by Service;
- Presentation tier -> handled by Controllers and JSP pages.
 
##  Technologies used:
- Java for service (I'm using version 17.0.3.1)
- IntelliJ IDEA (I'm using IntelliJ IDEA 2021.2.2 Ultimate Edition)
- Maven for service (I'm using version 3.8.6)
- JDBC for connection to DB
- MySQL as database (I'm using version 8.0.22)                                 
- Apache Tomcat as web server (I'm using version 9.0.50)
- JSP for presentation
- Java Servlet API for presentation (I'm using version 4.0.1)
- JSTL for presentation

## Features:
- registration like a driver;
- authentication lile a driver;
- create/update/remove a manufacturer;
- create/update/remove a driver;
- create/update/remove a car;
- display list of all manufacturers;
- display list of all drivers;
- display list of all cars;
- add driver to car;

## How to launch the project on your PC:

- Fork this repo
- Create schema and all tables using the file init_db.sql
- Config ConnectionUtil.class (you need write your own data in these constants)
  ~~~java
  private static final String URL = "URL";
  private static final String USERNAME = "USERNAME";
  private static final String PASSWORD = "PASSWORD";
  private static final String JDBC_DRIVER = "JDBC_DRIVER";
  ~~~
- Install Tomcat. I am using Tomcat 9.0.50.
- Add Tomcat server to configuration
- Run project
