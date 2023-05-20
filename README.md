# 🚖 My taxi-service 🚖
## Project description:
This is web application that supports authentication, registration and other CRUD operations.

![image](https://github.com/Vasyl-Piznak/my-taxi-service/assets/106866989/fa35627d-2e25-4680-b481-151a47ddb4c2)
 
## <img height="30" src="https://cdn-icons-png.flaticon.com/512/2857/2857406.png" width="36"> Project structure:
- Data access tier -> handled by DAO;
- Business logic tier -> handled by Service;
- Presentation tier -> handled by Controllers and JSP pages.
 
## <img height="30" src="https://edps.europa.eu/sites/default/files/picture/technologies2.png" width="36"/> Technologies used:
- Java for service (I'm using version 17.0.3.1)
- IntelliJ IDEA (I'm using IntelliJ IDEA 2021.2.2 Ultimate Edition)
- Maven for service (I'm using version 3.8.6)
- JDBC for connection to DB
- MySQL as database (I'm using version 8.0.22)                                 
- Apache Tomcat as web server (I'm using version 9.0.50)
- JSP for presentation
- Java Servlet API for presentation (I'm using version 4.0.1)
- JSTL for presentation

## <img height="30" src = "https://i.pinimg.com/564x/d5/1d/8b/d51d8b2ff28db324ed1be2766f793c43.jpg" width="36"/> DataBase structure:

## <img height="30" src = "https://cdn4.iconfinder.com/data/icons/scrum-process-2/64/product-capability-ability-features-requirements-512.png" width="36"/> Features:
- Registration like a driver;
- Authentication lile a driver;
- Create/update/remove a manufacturer;
- Create/update/remove a driver;
- Create/update/remove a car;
- Display list of all manufacturers;
- Display list of all drivers;
- Display list of all cars;
- Add driver to car;


## <img height="30" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXQZfgbHHUnh8EnFosVBvL1Q9zxQAuNrlmEzCQBAGzc7VihcwrsyRzGRBuvseJz4P-0OM&amp;usqp=CAU" width="36"/>  How to launch the project on your PC:

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
