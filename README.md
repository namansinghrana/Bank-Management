# Banking App

This is a demo project for a Spring Boot banking application.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Banking App is a Spring Boot application designed to manage banking operations. It uses Spring Data JPA for database interactions and connects to a MySQL database.

## Features
- User account management
- Transaction management
- Balance inquiry
- Fund transfer

## Technologies Used
- Java 17
- Spring Boot 3.2.3
- Spring Data JPA
- MySQL
- Lombok

## Setup Instructions
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/banking-app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd banking-app
    ```
3. Update the MySQL database configuration in `application.properties`:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/yourdatabase
    spring.datasource.username=yourusername
    spring.datasource.password=yourpassword
    ```
4. Build the project using Maven:
    ```bash
    mvn clean install
    ```
5. Run the application:
    ```bash
    mvn spring-boot:run
    ```

## Usage
Once the application is running, you can access the API endpoints to manage user accounts and transactions. Use tools like Postman or cURL to interact with the API.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.
