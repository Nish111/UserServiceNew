# UserService

## Overview
The **UserService** is a microservice responsible for managing user-related functionalities in the eCommerce platform. It provides APIs for user registration, authentication, profile management, and password reset.

This service ensures secure handling of user data and integrates seamlessly with other microservices in the system.

---

## Features
- User registration and login
- Secure password management with encryption
- Profile management (view and update user details)
- Token-based authentication using S2S
- Integration with Kafka for event-driven actions (e.g., sending welcome emails upon registration)

---

## Technologies Used
- **Java 8** (Programming Language)
- **Spring Boot** (Backend Framework)
- **MySQL** (Relational Database)
- **Kafka** (Message Broker)
- **S2S** (Authentication)
- **Docker** (Containerization)
- **Redis** (Caching for token storage)

---

## Installation

### Prerequisites
1. Ensure you have the following installed:
   - Java 8 or higher
   - MySQL
   - Kafka
   - Docker (optional for containerized deployment)
2. Clone the repository:
   ```bash
   git clone https://github.com/username/UserServiceNew.git
   cd UserServiceNew
