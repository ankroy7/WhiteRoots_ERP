# Spring Boot Backend Setup Instructions

## Prerequisites
- Java 11 or higher installed
- Maven installed
- An IDE such as IntelliJ IDEA or Eclipse

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ankroy7/WhiteRoots_ERP.git
   cd WhiteRoots_ERP
   ```

2. **Import the project into your IDE**:
   - Open your IDE and import the Maven project.

3. **Database Configuration**:
   - Configure your database details in `src/main/resources/application.properties`:
     ```properties
     spring.datasource.url=jdbc:mysql://<DB_HOST>:<DB_PORT>/<DB_NAME>
     spring.datasource.username=<DB_USERNAME>
     spring.datasource.password=<DB_PASSWORD>
     spring.jpa.hibernate.ddl-auto=update
     ```
   - Replace `<DB_HOST>`, `<DB_PORT>`, `<DB_NAME>`, `<DB_USERNAME>`, and `<DB_PASSWORD>` with your actual database configurations.

4. **Run the application**:
   - Use Maven to build and run the application:
   ```bash
   mvn spring-boot:run
   ```

## API Details
- Base URL: `http://localhost:8080/api`

### Endpoints
- **GET /api/endpoint**: Description of this endpoint.
- **POST /api/endpoint**: Description of this endpoint.

[Add more endpoints and their descriptions as needed.]