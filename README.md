# Ollama as a Service

This repository provides the necessary Kubernetes Deployment and Service YAML files to deploy the Ollama service on a Kubernetes cluster. It is designed for developers and DevOps professionals seeking a streamlined setup for AI/ML services on platforms like AWS EKS.

## Prerequisites

- A running Kubernetes cluster (e.g., AWS EKS)
- `kubectl` configured to interact with your cluster
- Basic knowledge of Kubernetes deployments and services

## Deployment Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/omers/ollama-as-service.git
   cd ollama-as-service

## Apply the Deployment and Service Configurations

```bash
kubectl apply -f ollama.yaml
```
