# ModernDevOps WeatherApp

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tech Stack](#tech-stack)

## Overview
This project is a microservices-based weather application, built to practice various DevOps techniques. It demonstrates containerization, orchestration, and automation. The application provides weather data and includes user authentication.

## Features
- Microservices Architecture: The application is divided into frontend (UI) and backend (Go and Python-based services).
- Database: MySQL is used for data persistence.
- Helm: Helm is used for Kubernetes deployment.
- Authentication: The application includes basic auth services.

## Prerequisites
- Docker
- Kubernetes
- Helm
- Git

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ahmedalaa14/moderndevops-weatherapp.git
    cd moderndevops-weatherapp
    ```

2. Build and run using Docker Compose:
    ```bash
    docker-compose up --build
    ```

3. For Kubernetes deployment, use Helm:
    ```bash
    helm install weatherapp ./helm/
    ```

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Go, Python
- **Database**: MySQL
- **Containerization**: Docker
- **Orchestration**: Kubernetes
- **Authentication**: Custom auth service
- **Package Management**: Helm
























