# CI/CD and IaC with Docker

## Introduction
This project demonstrates a basic CI/CD pipeline using GitHub Actions with Infrastructure as Code (IaC) implemented using Docker Compose. The pipeline builds and deploys a static web application inside a Docker container.

## CI/CD Pipeline
- The pipeline triggers on any push to the `main` branch.
- It uses Docker Compose to build and run the infrastructure.

## IaC with Docker Compose
- Docker Compose defines the infrastructure (a containerized web server).
- The web server serves a static website on port 8080.

## Integration
- GitHub Actions automates the build and deployment process.
- Docker Compose provisions and starts the infrastructure.

## Conclusion
This project simplifies deployment and infrastructure management by integrating CI/CD pipelines with IaC using Docker.
