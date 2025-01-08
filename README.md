# CI/CD Pipeline with GitHub Actions

This repository demonstrates a CI/CD pipeline for a simple Flask application.

## Features
- Python application with Flask
- Unit testing with `unittest`
- Docker image creation
- GitHub Actions workflow for CI/CD

## How to Use
1. Clone the repository.
2. Run `docker build -t ci-cd-demo .` to build the Docker image.
3. Run `docker run -p 5000:5000 ci-cd-demo` to start the application.
