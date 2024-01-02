# Publisher Register

This repository contains a Publisher Register project that manages publishers and their details. The backend is developed using Spring Boot, while the frontend is built with ReactJS.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Publisher Register project aims to provide a system to manage information about publishers. It allows users to add, update, and delete publisher details within the system.

## Features

- **Publisher Management:** Add, view, update, and delete publisher information.
- **Search Functionality:** Search for publishers based on various parameters.
- **User Authentication:** Secure access to the system via user authentication.

## Technologies Used

- **Backend:**
  - Spring Boot - Java-based framework for building the backend API.

- **Frontend:**
  - ReactJS - JavaScript library for building the user interface.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/MassimilianoVisintainer/publisher_register.git
2. Navigate to the backend directory (publisher_register/publisher_register_backend) and set up the backend:
    ```bash
   cd publisher_register/backend
3. Database Setup:
    - Ensure you have the required database (e.g., MySQL, PostgreSQL) installed and running locally.
    - Configure the database connection properties in the backend application. This typically involves editing the application.properties file.
4. Build and Run the Backend:

 - If using Maven, run the following commands:

    ```bash
    # Build the project
    ./mvnw clean package
    
    # Run the Spring Boot application
    java -jar target/backend-application.jar

Replace backend-application.jar with the actual name of your Spring Boot application JAR file

- Alternatively, you might run the application directly:

    ```bash
    # Run the Spring Boot application (if no build required)
    ./mvnw spring-boot:run

5. After starting the backend successfully, it should be available at http://localhost:8080 or the port specified in your application.

## Usage
Once the application is up and running, you can perform the following actions:

- Navigate to the home page.
- Use the provided interface to add, update, or delete publisher information.
- Search for publishers using the search functionality.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature).
3. Make your changes.
4. Commit your changes (git commit -m 'Add your feature').
5. Push to the branch (git push origin feature/your-feature).
6. Create a pull request.
7. Create a new branch (git checkout -b feature/your-feature).
8. Make your changes.
9. Commit your changes (git commit -m 'Add your feature').
10. Push to the branch (git push origin feature/your-feature).
7. Create a pull request.
