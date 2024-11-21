
# Dress Rental App 

Dress Rental App is a backend application developed with Java Spring Boot. This project is designed to practice topics such as creating web services, RESTful API development, database operations with Spring Boot and error management.


## Features

- **Spring Boot:** Used to develop RESTful API.
- **Database Integration:** CRUD operations are demonstrated using Spring Data JPA.
- **Error Management:** Effective error management and exception catching mechanisms are implemented throughout the application.
- **Transaction Management:** Transaction management is provided for database transactions


## Technologies

- **Java 17:** Main programming language used for backend logic.
- **Spring Boot:** Used for rapid development of RESTful services.
- **Spring Data JPA:** A Spring module that simplifies database operations.
- **Spring Security:** A Spring module that manages security, authentication and authorization processes.
- **Maven:** Project dependency management and compilation operations.
- **Docker & Docker Compose:** Used to run the application and MSSQL database as a container.
- **MSSQL:** Used as a database management system.
- **Junit - Mockito:** Used for application unit testing.


## Getting Started

### Requirements

To run the project, you must have the following software installed on your system:

- Java 17 or later
- Maven 3.8 or later
- Docker and Docker Compose (optional)
- IntelliJ IDEA or another IDE
- MSSQL or another compatible SQL database
- Swagger or Postman

### Installation

1. **Clone the project:**

   ```bash
   git clone https://github.com/irem-yigit/dress-rental-app.git
   ```

2. **Configure the database:**

   - Create a database named `dressrental` (this step is not necessary if running with Docker).
   - Update the `application.properties` file in the `src/main/resources` folder according to your database information.

3. **Build the project with Maven:**

   ```bash
   mvn clean install
   ```

4. **Run the Spring Boot application:**

   ```bash
   mvn spring-boot:run
   ```

   Once the application is launched, you can start using the APIs.

5. **Running with Docker (optional):**

   To run the application with Docker, you can use the `docker-compose.yml` file located in the root directory of the project:

   ```bash
   docker-compose up --build
   ```

## API Endpoints

Dress Rental App offers the following endpoints:

- `GET /dresses`: Gets a list of all available dresses.
- `POST /dresses`: Adds a new dress to the inventory.
- `PUT /dresses/{id}`: Updates the details of an existing dress. This is where we perform the rental process.

## Contributors

This project is developed by Java Backend Development Academy.

## License

This project is licensed under the MIT License. See `LICENSE` file for more information.
