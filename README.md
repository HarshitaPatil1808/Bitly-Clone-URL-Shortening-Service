# Bitly Clone – URL Shortening Service

A full-stack URL shortening platform inspired by Bitly, built with **Spring Boot**, **React**, **MySQL**, **Redis**, **Docker**, and **AWS**.

---

## Features

- **Secure Authentication**: JWT-based authentication with role-based access control.
- **URL Shortening**: Generate short URLs with optional custom aliases.
- **Link Management**: View, edit, and delete shortened URLs.
- **Analytics Dashboard**: Track URL clicks, referrers, and geographical data.
- **Custom Redirects**: Redirect to original URLs securely.
- **Caching**: Redis caching for faster URL resolution.
- **Scalable Deployment**: Dockerized application deployed on AWS with custom domain setup.

---

## Tech Stack

- **Backend**: Spring Boot, MySQL, Redis
- **Frontend**: React, Tailwind CSS
- **Deployment**: Docker, AWS EC2/S3
- **Authentication**: JWT

---

## Getting Started

### Prerequisites

- Java 17+
- Node.js 18+
- Docker
- MySQL
- Redis

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/HarshitaPatil1808/BitlyClone.git
   cd BitlyClone/backend
Configure database in application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/bitlydb
spring.datasource.username=root
spring.datasource.password=yourpassword


Start Redis server locally or configure cloud Redis.

Build and run backend:

./mvnw clean install
./mvnw spring-boot:run

Frontend Setup

Navigate to frontend directory:

cd ../frontend


Install dependencies:

npm install


Run the frontend:

npm start


Open http://localhost:3000
 to view the app.

Deployment

Dockerized backend and frontend for consistent deployment.

AWS deployment with EC2 for the app and S3 for static assets.

Redis caching for scalable and fast URL resolution.

Screenshots

(Add screenshots of the dashboard, URL shortening page, and analytics)

License

MIT License © 2025 Harshita Patil
