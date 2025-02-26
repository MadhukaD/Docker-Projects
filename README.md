# Docker Projects Repository

Welcome to my Docker projects repository! í ½íº€ This repository contains source codes and configurations for **10 Docker-based projects** that I have worked on. Each project includes a `Dockerfile`, necessary configurations, and setup instructions.

## Projects Overview

### 1. **Flask App with PostgreSQL**
- A simple Flask web application that connects to a PostgreSQL database using Docker Compose.
- **Tech Stack:** Flask, PostgreSQL, Docker, Docker Compose
- **Files:**
  - `app.py`
  - `Dockerfile`
  - `docker-compose.yml`
  - `requirements.txt`

### 2. **Node.js & MongoDB REST API**
- A REST API built with Node.js and Express, using MongoDB as the database.
- **Tech Stack:** Node.js, Express, MongoDB, Docker
- **Files:**
  - `server.js`
  - `Dockerfile`
  - `docker-compose.yml`
  - `package.json`

### 3. **Nginx Reverse Proxy**
- A Docker setup with Nginx acting as a reverse proxy for multiple backend services.
- **Tech Stack:** Nginx, Docker, Reverse Proxy
- **Files:**
  - `nginx.conf`
  - `Dockerfile`
  - `docker-compose.yml`

### 4. **Django with PostgreSQL & Redis**
- A Django-based web application using PostgreSQL as the database and Redis for caching.
- **Tech Stack:** Django, PostgreSQL, Redis, Docker
- **Files:**
  - `app/`
  - `Dockerfile`
  - `docker-compose.yml`
  - `requirements.txt`

### 5. **React Frontend with Express Backend**
- A full-stack React application with an Express.js backend, both containerized.
- **Tech Stack:** React, Node.js, Express, Docker
- **Files:**
  - `client/`
  - `server/`
  - `Dockerfile`
  - `docker-compose.yml`

### 6. **MySQL & PHP Web App**
- A simple PHP application that connects to a MySQL database using Docker.
- **Tech Stack:** PHP, MySQL, Docker
- **Files:**
  - `index.php`
  - `Dockerfile`
  - `docker-compose.yml`

### 7. **WordPress with MySQL**
- A WordPress setup running in a Docker container with MySQL as the database.
- **Tech Stack:** WordPress, MySQL, Docker
- **Files:**
  - `docker-compose.yml`

### 8. **ELK Stack (Elasticsearch, Logstash, Kibana)**
- A centralized logging system using the ELK stack in Docker.
- **Tech Stack:** Elasticsearch, Logstash, Kibana, Docker
- **Files:**
  - `docker-compose.yml`
  - `logstash.conf`

### 9. **Jenkins CI/CD in Docker**
- A Jenkins setup running in a Docker container for CI/CD pipelines.
- **Tech Stack:** Jenkins, Docker
- **Files:**
  - `Dockerfile`
  - `docker-compose.yml`

### 10. **Kafka & Zookeeper Cluster**
- A Dockerized Apache Kafka and Zookeeper cluster.
- **Tech Stack:** Apache Kafka, Zookeeper, Docker
- **Files:**
  - `docker-compose.yml`
  - `kafka-config/`

---

## Getting Started

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/docker-projects.git
   cd docker-projects
   ```

2. **Run a Specific Project:**
   ```sh
   cd flask-postgres-app  # Change directory to the desired project
   docker-compose up -d   # Start the containers
   ```

3. **Stop Containers:**
   ```sh
   docker-compose down
   ```

---

## Prerequisites
- Install [Docker](https://www.docker.com/)
- Install [Docker Compose](https://docs.docker.com/compose/install/)
- Ensure required dependencies (Node.js, Python, etc.) are installed if running manually

---

## Contribution
Feel free to submit **pull requests** or report issues if you find any bugs or improvements!

---

## License
This project is licensed under the MIT License.

Happy Dockering! í ½íº¢


