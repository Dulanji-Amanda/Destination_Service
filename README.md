# 🌍 Destination Service

## 📌 Project Overview
The Destination Service manages core travel entities in the TripDiary application, including travel destinations, blogs, and user reviews. It uses MongoDB as the primary database for fast and flexible data storage.

---

## 🎯 Mandatory Information
- **Student Name**: Dulanji Amanda Sathsarani
- **Student Number**: 241722009
- **GCP Project ID**: project-00e6ad8d-07ac-4315-820

---

## 🛠 Technology Stack
- Java 25
- Spring Boot 3.4.x
- Spring Data MongoDB
- Spring Cloud Netflix Eureka Client
- Maven
- Google Cloud Platform (GCP)
- PM2 (Process Manager)

---

## 🚀 Setup / Getting Started Instructions

### Prerequisites
- JDK 25 installed
- Maven installed
- MongoDB connection string configured
- Eureka Server and Config Server must be running

### Installation & Execution
1. Clone the repository and navigate to the directory:
   ```bash
   cd destination-service
   ```
2. Build the project:
   ```bash
   mvn clean install
   ```
3. Run the application:
   ```bash
   mvn spring-boot:run
   ```
The service will start on port `8082`.
