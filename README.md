# User Registration and Authentication System

This project demonstrates the development of a user registration and authentication system using Java Spring Boot, Spring JPA, Spring Security, and PostgreSQL. The system provides a secure and user-friendly way for users to register, verify their email addresses, and gain access to authenticated features.

## Technologies Used

- Java
- Spring Boot
- Spring JPA (Java Persistence API)
- Spring Security
- PostgreSQL

## Project Overview

The project aims to create a robust backend system that facilitates user registration, email verification, and secure authentication. It involves the following components:

### User Registration

- Implemented a user-friendly registration process using a POST endpoint.
- Leveraged Spring MVC architecture to handle registration requests.
- Utilized Spring JPA to manage the database schema, including the 'Appuser' and 'ConfirmationToken' tables.

### Email Verification

- Developed a secure email verification process with token generation.
- Utilized an external CURL email service to send verification emails.
- Enforced a strict 15-minute time constraint for email verification using token expiration logic.

### Secure Authentication

- Incorporated Spring Security mechanisms to enhance system security.
- Ensured authenticated users gain exclusive access to authenticated features post email verification.

## Usage

1. Clone the repository to your local machine.
2. Configure your PostgreSQL database settings in the `application.properties` file.
3. Run the Spring Boot application.
4. Access the application through the primary localhost page.
5. Register as a new user, following the user-friendly registration process.
6. Receive a verification email with a generated token for email confirmation.
7. Verify your email address within the stipulated time (15 minutes) by clicking the provided link.
8. Gain access to authenticated features upon successful verification.

## API Endpoints

- **POST /register**: Register a new user.
- **GET /confirm/{token}**: Verify the email address by confirming the token.

## Validation

The system's API endpoints have been thoroughly validated using tools like Postman. Essential scenarios, such as user registration via POSTMapping and token verification via getMapping, have been covered to ensure the robustness and reliability of the system.


