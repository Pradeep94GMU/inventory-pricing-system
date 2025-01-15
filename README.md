# Inventory Pricing System

## Description
This project is a simple microservices-based system for managing inventory and dynamic pricing. It includes the following services:
- Inventory Service
- Pricing Service

## Technologies Used
- Java 17
- Spring Boot
- Kafka for messaging
- MySQL for database storage
- MongoDB for pricing logs
- Asynchronous communication
- Concurrency handling with Java features

## Microservices
- **Inventory Service**: Manages stock levels and replenishment.
- **Pricing Service**: Adjusts prices based on stock levels, demand, and market conditions.

## Architecture
- A high-level description of how the services interact.
- Includes communication between the services using asynchronous messaging (Kafka).
- Two databases: MySQL for inventory and MongoDB for price logs.

## How to Run the Project
1. Clone the repository: `git clone https://github.com/Pradeep94GMU/inventory-pricing-system.git`
2. Navigate to the project folder.
3. Run the project using: `mvn spring-boot:run`
4. Access the application at `http://localhost:8080`

## Future Features
- Automated pricing updates based on competitor prices.
- Real-time stock level updates with notifications.

