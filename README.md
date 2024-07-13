**Pass-In - Participant Management Application for In-Person Events**

### About the Project

Pass-In is an application designed for managing participants at in-person events. It enables organizers to register events, open public registration pages, and efficiently manage participant check-ins through digital credentials and QR code scanning.

### Features

- **Event Management:** Organizers can create and view event details.
- **Participant Registration:** Participants can register for events and view their registration badge.
- **Check-In System:** Conduct event check-ins via QR code on the badge.

### Getting Started

#### Prerequisites

- JDK (Java Development Kit)
- Maven
- Preferred Java IDE (IntelliJ IDEA, Eclipse, etc.)

#### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Taimisson/Pass-In.git
    ```
2. Navigate to the project directory and install dependencies:
    ```bash
    mvn install
    ```
3. Run the application:
    ```bash
    mvn spring-boot:run
    ```

### Technologies Used

This project uses Java for the backend, Maven for dependency management, and Spring Boot for simplified configuration and setup. The application features a REST API for efficient front-back communication, integrates with the HSQL database for data storage, uses JPA for data persistence, Flyway for database migrations, and DTOs (Data Transfer Objects) for efficient data handling across different layers of the application.

### Contribution

Contributions are welcome! Please read the contribution guidelines for more information.

### License

Distributed under the MIT license. See the LICENSE file for more information.
