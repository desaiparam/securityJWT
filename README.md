JWT Token Generator with Spring Boot

This project is a Java application built with Spring Boot and Maven that generates JSON Web Tokens (JWT) for secure authentication.

Features

	•	JWT Authentication: Secure your API endpoints with JWT-based authentication.
	•	Spring Boot: Leverages the power of Spring Boot for rapid development.
	•	Maven: Built using Maven for dependency management and build automation.

Getting Started

Prerequisites

	•	Java 17 or higher
	•	Maven 3.8.1 or higher
	•	Git
Endpoints

	•	/authenticate: Endpoint to generate JWT token.
	•	/secure: A secured endpoint that requires a valid JWT token.

Usage

	1.	To generate a token, send a POST request to /authenticate with the required credentials.
	2.	Use the generated JWT token in the Authorization header as Bearer <token> to access secured endpoints.

Configuration

You can configure various settings like secret keys, token expiration times, etc., in the application.properties file.

Security

	•	JWT Token: Ensure that you keep your secret keys safe and secure.
	•	Environment Variables: Store sensitive information, like keys and credentials, as environment variables.
