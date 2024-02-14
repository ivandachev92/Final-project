# DevOps Final Project

This project is the final assignment for the DevOps course at Pragmatic. It sets up a Jenkins server on an AWS EC2 instance using Terraform and configures it with Docker, Kubernetes, and Helm.

## Project Structure

- `Dockerfile`: Defines the Docker image for the application.
- `helm/`: Contains the Helm chart for deploying the application on Kubernetes.
- `terraform/`: Contains the Terraform scripts for provisioning the AWS infrastructure.
- `web.py`: The Python script for the web application.

## Key Features

- Provisions an AWS EC2 instance with Jenkins installed.
- Configures Jenkins with Docker, allowing it to build Docker images.
- Installs Kubernetes and Helm on the Jenkins server.
- Sets up a Kubernetes cluster using Kind.
- Creates an ECR repository for storing Docker images.

## How to Use

1. Navigate to the `terraform/` directory and run `terraform init` and `terraform apply`.
2. Once the infrastructure is set up, you can access the Jenkins server at the public IP of the EC2 instance.

Please note that this project is for educational purposes and may not be suitable for production environments.
