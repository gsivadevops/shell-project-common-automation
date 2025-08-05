# shell-project-common-automation
Shell Project Automation with common code

# roboshop-shell-project

This project contains Shell scripts to automate the setup of the RoboShop application, which is a microservices-based e-commerce application used for DevOps learning and practice.

## Project Overview

RoboShop has multiple microservices like frontend, catalogue, user, cart, payment, shipping, and supporting tools like MongoDB, MySQL, RabbitMQ, and Redis. These scripts help set up all of them easily on supported systems.

## What This Project Includes

- Setup scripts for:
  - Frontend (Nginx)
  - Backend services (Node.js, Python, Java)
  - Databases (MongoDB, MySQL)
  - Messaging and caching (RabbitMQ, Redis)
  - A common.sh file to handle reusable logic (like status checks and logging)
- Easy to run from a single terminal

## Folder Contents
- `frontend.sh` – Installs and configures the frontend
- `catalogue.sh`, `user.sh`, `cart.sh` – Node.js services
- `payment.sh` – Python service
- `shipping.sh` – Java service
- `mongodb.sh`, `mysql.sh` – Databases
- `redis.sh`, `rabbitmq.sh` – Support services
- `common.sh` – Common reusable functions
