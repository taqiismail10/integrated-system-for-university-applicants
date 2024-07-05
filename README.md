# Integrated System for University Applicants

## Introduction

This project is designed to streamline the university application process for students in Bangladesh. It allows students to fill out a single, standardized application form that can be submitted to multiple universities, making the process more efficient and less error-prone.

## Technologies Used

- **Spring Boot**: For building the backend services.
- **MySQL**: As the database for storing application data.
- **Spring Data JPA**: For data access and persistence.
- **Thymeleaf**: For server-side rendering of HTML.
- **Spring Security**: For securing the application.

## Getting Started

### Prerequisites

- Java 11 or later
- Maven 3.6.3 or later
- MySQL 8.0 or later

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/integrated-system-for-university-applicants.git
    cd integrated-system-for-university-applicants
    ```

2. Update the database configuration in `src/main/resources/application.properties`:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/university_db
    spring.datasource.username=root
    spring.datasource.password=yourpassword
    spring.jpa.hibernate.ddl-auto=update
    spring.jpa.show-sql=true
    ```

3. Run the application:
    ```sh
    mvn spring-boot:run
    ```

### Usage

- Access the application at `http://localhost:8080`.
- Follow the instructions to register, apply to universities, and track application status.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
