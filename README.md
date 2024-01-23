Title : Containerisation and Deployment of Wisecow Application on Kubernetes

Objective: To containerize and deploy the Wisecow application, hosted in the above-mentioned GitHub repository, on a Kubernetes environment with secure TLS communication.

1. Dockerization:
● Developed a Dockerfile for creating a container image of the Wisecow application.

2. Kubernetes Deployment:
● Crafted Kubernetes manifest files for deploying the Wisecow application in a Kubernetes environment.
● The Wisecow app  exposed as a Kubernetes service for accessibility.

3.Continuous Integration and Deployment (CI/CD):
● Implemented a GitHub Actions workflow for:
● Automating the build and push of the Docker image to a container registry whenever changes are committed to the repository.
● Continuous Deployment [Challenge Goal]: Automatically deploy the updated application to the Kubernetes environment following successful image builds.
