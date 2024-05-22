# Hello World Express Application

This is a simple "Hello World" application built with index.js (which provided) and Docker. The application listens on port 3000 inside the container but is exposed on port 8080 on the host machine.

## Prerequisites

- Docker
- Docker Compose
- Jenkins (for CI/CD pipeline)
- node js

## Project Structure

- `Dockerfile`: Defines the Docker image for the application.
- `docker-compose.yml`: Defines the Docker Compose configuration for the application.
- `index.js`: The main application file.
- `package.json`: The npm package configuration file.

## Jenkins Integration
This project includes Jenkins for continuous integration and continuous deployment. Jenkins uses Docker and Docker Compose to build and deploy the application. To set up Jenkins for this project, ensure you have the following Jenkins plugins installed:

Docker,
Docker-api,
Docker Pipeline,
Git,
Pipeline,
nodejs.

