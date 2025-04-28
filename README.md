# k8s-demo

Demo Project to use Kubernetes (k8s) with Minikube.

## Overview

This project is a demonstration of deploying and managing applications using Kubernetes and Minikube. It provides a simple setup to help developers understand the fundamentals of Kubernetes, including pods, services, and deployments.

## Prerequisites

Before using this project, ensure you have the following installed:

- [Minikube](https://minikube.sigs.k8s.io/docs/start/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- Docker (optional, if building container images locally)

## Project Structure

The repository contains the following key components:

- **Manifests**: Kubernetes YAML files for deploying the application.
- **Dockerfile**: To build the container image for the application.
- **Source Code**: Example application code (if applicable).

## Getting Started

Follow these steps to run the project locally using Minikube:

1. Start Minikube:
   ```bash
   minikube start
2. Apply the Kubernetes manifests:
   ```bash
   kubectl apply -f manifests/
3. Verify the deployment:
   ````bash
   kubectl get pods
   kubectl get services
4. Access the application: Use the Minikube service URL to access the application. Run the following command to get the URL:
   ````bash
   minikube service <service-name>

   Features
Demonstrates basic Kubernetes objects (Pods, Services, Deployments).
Provides a foundation for learning and experimenting with Kubernetes.
Compatible with local Minikube environments.
Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for any improvements or suggestions.

License
This project is licensed under the MIT License. See the [LICENSE file](LICENSE) for more details.

Acknowledgments
[Kubernetes Documentation](https://kubernetes.io/docs/)
[Minikube Documentation](https://minikube.sigs.k8s.io/docs/)
