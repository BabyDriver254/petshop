# PetShop -- Microservices E-Commerce Platform

PetShop is a fully containerized microservices-based e-commerce
application built with **Spring Boot**, **Angular**, **Auth0**,
**Docker**, **Kubernetes**, and **Jenkins CI/CD**.\
It demonstrates a real cloud-ready architecture with authentication,
routing, centralized configuration, service discovery, deployment
automation, and a modern Angular frontend.

### Frontend / Gateway:
- https://34.54.201.1.sslip.io/

## 🚀 Architecture Overview

    ... (diagram omitted for brevity in this preview; full in file)

## 🧩 Microservices & Repositories

### Backend Services

-   **Product Service**\
    https://github.com/IslamHamada/petshop_productservice
-   **Cart Service**\
    https://github.com/IslamHamada/petshop_cartservice
-   **Order Service**\
    https://github.com/IslamHamada/petshop_orderservice
-   **User Service**\
    https://github.com/IslamHamada/petshop_userservice

### Infrastructure

-   **API Gateway**\
    https://github.com/IslamHamada/petshop_gateway
-   **Config Server**\
    https://github.com/IslamHamada/petshop_configserver
-   **Service Registry**\
    https://github.com/IslamHamada/petshop_serviceregistry

### Shared

-   **Shared Contracts**\
    https://github.com/IslamHamada/petshop_contracts
-   **Shared Config**\
    https://github.com/IslamHamada/petshop_sharedconfig

### Frontend

-   **Angular UI**\
    https://github.com/IslamHamada/petshop-ui

### Deployment

-   **Deployment Repository (docker‑compose + K8s + MySQL)**\
    https://github.com/IslamHamada/petshop_deployment

## 🛠️ Tech Stack

-   Java 17, Spring Boot 3.x, Spring Cloud
-   Angular, Angular Material, Auth0
-   Docker, Jib, Jenkins, Kubernetes, GKE

## ✨ Features

-   Auth0 login
-   Product catalog
-   Cart & Order pipeline
-   Gateway routing & JWT validation
-   Centralized config + Eureka discovery
-   CI/CD to GKE
