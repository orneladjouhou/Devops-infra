
# Microservice Application Deployment on Kubernetes

This project demonstrates the deployment of a simple Python-based Hello World microservice application on Kubernetes, along with additional features like logging, monitoring, and optional CI/CD pipeline setup.

## Project Structure

The project is organized as follows:

- **hello.py**: Simple Python-based Hello World application.
- **Dockerfile**: Dockerfile for containerizing the Python application.
- **deployment.yaml**: Kubernetes Deployment manifest.
- **service.yaml**: Kubernetes Service manifest.
- **ingress.yaml**: Kubernetes Ingress manifest.
- **.gitlab-ci.yml**: GitLab CI configuration (for CI/CD).

## 1. Containerize a Simple Application

### Prerequisites

- Docker installed.

### Steps

1. Create a Python-based Hello World application in `hello.py`.
2. Create a Dockerfile with instructions for building the Docker image.
3. Execute the following command to build the Docker image:

   ```bash
   docker  build -t hello-world-app:v2 .
