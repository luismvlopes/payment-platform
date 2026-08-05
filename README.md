# Payment Platform

A modern payment platform built with **Java 21** and **Spring Boot 3**, designed to demonstrate backend software engineering best practices and modern distributed system architecture.

> **Status:** 🚧 Work in Progress

---

## Overview

This project simulates a real-world payment platform similar to those used by banks and fintech companies.

It is being developed incrementally, starting as a **modular monolith** and progressively evolving into an **event-driven microservices architecture**.

The goal is not only to implement features, but also to showcase software engineering principles, architectural patterns, testing strategies, observability, and cloud-native technologies.

---

## Features (Planned)

* Customer management
* Accounts
* Digital wallets
* Money transfers
* Transaction history
* Payment events
* Notifications
* Authentication & Authorization
* Audit logging

---

## Technology Stack

### Backend

* Java 21
* Spring Boot 3
* Spring Security
* Spring Data JPA
* Hibernate
* Maven

### Database

* PostgreSQL
* Liquibase

### Messaging

* Apache Kafka

### Infrastructure

* Docker
* Docker Compose
* Kubernetes

### Cloud

* AWS S3
* GitHub Actions

### Testing

* JUnit 5
* Mockito
* Testcontainers

### Documentation

* OpenAPI / Swagger

### Observability

* Micrometer
* Prometheus
* Grafana

---

## Architecture Roadmap

The project will evolve through multiple stages:

* ✅ Repository initialization
* 🚧 Modular Monolith
* Event-Driven Architecture
* Outbox Pattern
* Microservices
* Security (JWT)
* Resilience
* Observability
* Kubernetes
* AWS Deployment
* CI/CD Pipeline

---

## Planned Architecture

```text
                        Clients
                           │
                           ▼
                     REST API Layer
                           │
                           ▼
                  Modular Monolith
        ┌───────────┬───────────┬───────────┐
        │ Customer  │ Account   │ Payment   │
        └───────────┴───────────┴───────────┘
                           │
                           ▼
                     PostgreSQL Database
```

Later versions will progressively introduce:

* Kafka
* Event-driven communication
* Outbox Pattern
* Dedicated microservices
* Kubernetes deployment
* Cloud infrastructure

---

## Project Goals

This repository aims to demonstrate practical experience with:

* Clean Architecture
* Domain-Driven Design (DDD)
* Event-Driven Architecture
* Microservices
* Resilience Patterns
* Software Testing
* CI/CD
* Cloud-Native Development
* Observability

---

## Development Status

This project is being developed incrementally following professional software engineering practices.

Each milestone introduces new concepts while keeping the application functional and production-oriented.

---

## License

Licensed under the MIT License.
