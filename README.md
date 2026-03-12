# Kubernetes Platform Demo

This project demonstrates deploying a containerized application to Kubernetes.

Components included:

- Docker container
- Kubernetes Deployment
- Kubernetes Service
- Kubernetes Ingress

The application is a simple FastAPI service built in a previous CI/CD project.

## Architecture

Developer
   │
Push code
   │
CI pipeline
   │
Build Docker image
   │
Push image → Container Registry
   │
Deploy to Kubernetes