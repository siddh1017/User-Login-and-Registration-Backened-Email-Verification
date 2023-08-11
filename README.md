# User-Login-and-Registration-Backened-Email-Verification
* Developed a robust backend system using Java Spring Boot framework, enabling user registration and authentication functionalities. Leveraged PostgreSQL database for seamless data storage.
* Implemented a user-friendly registration process, allowing open access through a POST endpoint. Utilized Spring MVC architecture for handling registration requests (POSTMapping).
* Designed and managed the database schema, comprising 'Appuser' and 'ConfirmationToken' tables, utilizing Spring JPA for efficient data persistence.
* Orchestrated a secure email verification process, involving the generation of tokens and sending verification emails using CURL email service.
* Enforced a stringent time constraint of 15 minutes for email verification, expiring the token upon lapse. Ensured robustness through token expiration logic.
* Strengthened system security by incorporating Spring Security mechanisms, securing the primary localhost page. Authenticated users gained exclusive access post email verification.
* Validated the system's API endpoints using Postman, covering essential scenarios such as user registration through POSTMapping and token verification via getMapping.
By skillfully combining Java Spring Boot, PostgreSQL, Spring JPA, Spring Security, and Postman testing, the backend system enabled smooth user registration, verification, and access control, contributing to a seamless user experience. This comprehensive approach underscores your commitment to quality assurance and thorough testing.
