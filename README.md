
# SpringSecurityJWT

* Implementation of Authorization and Authentication Using Spring Security

* It utilizes the JJWT library for JSON Web Token (JWT) implementation.

## Description

This is a backend application built using Spring Boot and Spring Security for authentication and authorization purposes. 
## Prerequisites

* Spring Boot
* Spring Security
* Core Java
* Hibernate
## Dependencies

* JJWT API
* JJWT Implementation
* JJWT Jackson
## Installation

1. Clone the repository:

    ```
    git clone https://github.com/Vijaykumar23112000/SpringSecurityJWT.git

    ```
2.  Navigate to the project directory:

    ```
    cd SpringSecurityJWT

    ```

3. Build the project using Maven:

    ```
    mvn clean install
    
    ```



## Configuration

* Update application.properties file with your database configuration.
* Feel free to customize security configurations in SecurityConfig.java according to your requirements.
## Usage

1 : Run the application:

    mvn spring-boot:run

2 : Once the application is running, you can access the API endpoints using a tool like Postman
## Authentication and Authorization

* Authentication is done using Spring Security's authentication mechanisms with JWT tokens provided by the JJWT library.

* Authorization is implemented using role-based access control (RBAC) defined in SecurityConfig.java.
## Contributions

* Contributions, including bug reports, feature requests, and code improvements, are welcome!