# TaskBoard.Zone.Boot
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

Task Board (Scalable WebApp Case Study)

# Overview

🚀 Welcome to **TaskBoard.Deployment.Boot** – your gateway to a fully containerized ecosystem of microservices designed to manage your tasks like sticky notes on a digital board. This project demonstrates modern microservices architecture using **Java**, **Spring Boot**, **Keycloak**, **APISIX**, and **Docker**.

## 🧩 Included Modules

This repository orchestrates the following microservices and frameworks via Git submodules:

- 🔐 [TaskBoard.Authenticator.Boot](https://github.com/niolikon/TaskBoard.Authenticator.Boot)
- 🧱 [TaskBoard.Framework.Boot](https://github.com/niolikon/TaskBoard.Framework.Boot)
- 📌 [TaskBoard.Service.Boot](https://github.com/niolikon/TaskBoard.Service.Boot)

## ✨ Features

- **Todo Management**: Manage To-dos with CRUD operations.
- **Dependency Injection**: Decouple components for better testability and maintainability.
- **Standardized Exception Handling**: Implements REST exception management following [RFC 7807 (Problem Details for HTTP APIs)](https://datatracker.ietf.org/doc/html/rfc7807).
- **Keycloak Authentication Integration**: Provides an authentication system that integrates with Spring Security OAuth and Keycloak.
- **Scenario-Based Testing**: Supports scenario-driven testing with JUnit extensions, annotations, and Spring Boot configurations.

## 🛠️ Getting Started

### Prerequisites

- **Docker or Podman** (instructions for Podman are not provided)


### Quickstart Guide

1. Clone the repository:
   ```bash
   git clone --recursive https://github.com/niolikon/TaskBoard.Zone.Boot.git
   cd TaskBoard.Zone.Boot
   ```

2. Configure credentials on a .env file as follows
   ```
    DB_NAME=todolist
    DB_USER=appuser
    DB_PASSWORD=apppassword
    KEYCLOAK_DB_PASSWORD=supersecretkeycloak
    KEYCLOAK_ADMIN_PASSWORD=adminpassword
   ```

3. Compose docker container
   ```bash
   docker-compose up -d
   ```

---

## 📬 Feedback

If you have suggestions or improvements, feel free to open an issue or create a pull request. Contributions are welcome!

---

## 📝 License

This project is licensed under the MIT License.

---
🚀 **Developed by Simone Andrea Muscas | Niolikon**

