![Service Discovery Banner](https://raw.githubusercontent.com/Vishnu-Yadav0/Revshop-service-discovery/main/banner.png)

# 🔍 RevShop — Service Discovery

Netflix Eureka Server that acts as the service registry for the entire RevShop platform. Every microservice registers itself here on startup and discovers other services dynamically — no hardcoded URLs anywhere.

[![Java](https://img.shields.io/badge/Java-17-orange?style=flat-square&logo=openjdk)](https://openjdk.org/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?style=flat-square&logo=springboot)](https://spring.io/projects/spring-boot)
[![Eureka](https://img.shields.io/badge/Netflix-Eureka%20Server-red?style=flat-square)](https://spring.io/projects/spring-cloud-netflix)
[![Docker](https://img.shields.io/badge/Docker-Containerized-blue?style=flat-square&logo=docker)](https://www.docker.com/)

---

## What it does

- Acts as the **service registry** for all 9 core microservices
- Services register on startup and deregister cleanly on shutdown
- Enables **client-side load balancing** via Spring Cloud LoadBalancer
- Provides a dashboard UI to monitor registered instances

## Tech Stack

| Layer | Tech |
|---|---|
| Framework | Spring Boot 3, Spring Cloud Netflix |
| Registry | Eureka Server |
| Container | Docker |

## Running Locally

> Start this before any other service.

```bash
./mvnw spring-boot:run
```

Eureka Dashboard: `http://localhost:8761`

## Default Port

`8761`

---

## Part of RevShop Microservices

| Service | Repo |
|---|---|
| 🌐 Frontend | [Revshop-frontend](https://github.com/Vishnu-Yadav0/Revshop-frontend) |
| ⚙️ API Gateway | [Revshop-api-gateway](https://github.com/Vishnu-Yadav0/Revshop-api-gateway) |
| 🔍 Service Discovery | [Revshop-service-discovery](https://github.com/Vishnu-Yadav0/Revshop-service-discovery) |
| 🗂️ Config Server | [Revshop-config-server](https://github.com/Vishnu-Yadav0/Revshop-config-server) |
| 👤 User Service | [Revshop-user-service](https://github.com/Vishnu-Yadav0/Revshop-user-service) |
| 🛍️ Product Catalog | [Revshop-product-catalog-service](https://github.com/Vishnu-Yadav0/Revshop-product-catalog-service) |
| 📦 Inventory | [Revshop-inventory-service](https://github.com/Vishnu-Yadav0/Revshop-inventory-service) |
| 🛒 Order/Sales | [Revshop-order-sales-service](https://github.com/Vishnu-Yadav0/Revshop-order-sales-service) |
| 💳 Payment | [Revshop-payment-service](https://github.com/Vishnu-Yadav0/Revshop-payment-service) |
| 🔔 Notification | [Revshop-notification-service](https://github.com/Vishnu-Yadav0/Revshop-notification-service) |
| 🚚 Shipping | [Revshop-shipping-service](https://github.com/Vishnu-Yadav0/Revshop-shipping-service) |
| 🤖 AI Chat | [Revshop-ai-chat-service](https://github.com/Vishnu-Yadav0/Revshop-ai-chat-service) |

