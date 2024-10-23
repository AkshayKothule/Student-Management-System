# Student-Management-System


# Spring Boot

# Annotations
@Component :-component is a special kind of class that can be autodetected by Spring IoC and used for dependency injection.
Components are mostly used to: Ensure a high level of decoupling between different parts of an application.

# Autowired

@Autowired is one of the core annotations in Spring, used for automatic dependency injection. 
In simpler terms, it allows Spring to automatically wire the required beans (dependencies) into your classes, 
eliminating the need for manual configuration

# Controller
@Controller :- controller is handles HTTP requests and returns responses to the client.
Controllers act as an intermediary between the client and the application's business logic.
They receive requests, process data, and determine a response, which can be HTML pages, JSON data, or redirects.

@RequestMapping: This is used to map to the Spring MVC controller method.

@ResponseBody: Used to bind the HTTP response body with a domain object in the return type.

@Entity: This annotation defines that a class can be mapped to a table

@Id: This annotation specifies the primary key of the entity.

@GeneratedValue: This annotation is used to specify the primary key generation strategy to use. i.e. Instructs database to generate a value for this field automatically. If the strategy is not specified by default AUTO will be used.

# Application Properties

application.properties file is used to write the application-related property into that file. 
This file contains the different configuration which is required to run the application in a different environment,
and each environment will have a different property defined by it.

Inside the application properties file, we define every type of property like changing the port, 
database connectivity, connection to the eureka server, and many more

JPA: JPA is a Java specification that is used to access, manage, and persist data between Java object and relational database. It is a standard approach for ORM.



