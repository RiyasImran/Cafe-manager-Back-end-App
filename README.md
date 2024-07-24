# Cafe Management Backend Application

## Overview

The **Cafe Management Backend Application** is designed to manage various aspects of cafe operations. It features a robust backend built with Java and Spring Boot, utilizing JWT for authentication, PostgreSQL for database management, and includes messaging and billing services. The application allows users to print bills as PDFs and access features based on their admin rights. Multiple JPA and native queries are implemented to support various functionalities.

## Features

- **User Authentication**: Secure access using JWT (JSON Web Tokens).
- **Billing Services**: Generate and print bills as PDFs.
- **Admin Rights**: Access to features based on user roles and admin rights.
- **Database Management**: Utilizes PostgreSQL for storing and managing data.
- **Messaging Services**: Implements messaging features for internal communication.
- **Query Support**: Uses JPA and native queries for efficient data retrieval and manipulation.

## Technologies Used

- **Backend**:
    - Java
    - Spring Boot
    - JWT (JSON Web Tokens)

- **Database**:
    - PostgreSQL

- **Services**:
    - PDF Generation
    - Messaging Services

## Installation

### Prerequisites

- Java JDK 11 or higher
- PostgreSQL
- Maven

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cafe-management-backend-application.git
2. Configure the application.properties file with your MySQL database credentials.
    ```bash
   spring.datasource.url=jdbc:postgresql://localhost:5432/cafemanagement
    spring.datasource.username=yourusername
    spring.datasource.password=yourpassword
3. Build the Spring Boot application:
    ```bash
    ./mvnw clean install
4. Start the Spring Boot application:
    ```bash
    ./mvnw spring-boot:run
### Usage

- API Endpoints: Access the API endpoints provided by the Spring Boot application to interact with the cafe management system.
- PDF Printing: Use the provided functionality to generate and print bills as PDFs

### Contributing

Feel free to fork the repository and submit pull requests. For any issues or feature requests, please open an issue in the GitHub repository.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Spring Boot for the backend framework.
- PostgreSQL for database management.
  Libraries and tools used for PDF generation and JWT authenticatio