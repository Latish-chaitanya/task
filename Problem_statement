task
 
Deploy a microservices-based web application to AWS using Kubernetes and Docker, with a CI/CD pipeline for automated deployments.

Application Setup:

Use a sample microservices-based web application (could be Node.js, Python, or .NET based) that consists of at least two services (e.g., a front-end UI and a back-end API).
Each service should be containerized using Docker, and must write Dockerfiles for each service.
Push the Docker images to AWS Elastic Container Registry (ECR).

Use AWS EKS (Elastic Kubernetes Service) to set up a Kubernetes cluster.
Define Helm charts or Kubernetes manifests to deploy both services (front-end and back-end) in the EKS cluster. This should include configuring services, ingresses, and autoscaling.
Ensure the deployment has horizontal pod autoscaling and a proper resource allocation setup (CPU/memory limits).

Create a CI/CD pipeline using AWS CodePipeline (or Jenkins, GitHub Actions, or Bitbucket Pipelines) that:
Automates the build and push of Docker images.
Deploys updated images to the EKS cluster whenever code is pushed to the GitHub repository.

Configure an AWS Application Load Balancer (ALB) to distribute traffic to the Kubernetes services.
Set up auto-scaling based on CPU/memory metrics and load testing the application to see if the scaling works.

Set up monitoring and logging for the application using AWS CloudWatch or Prometheus/Grafana for Kubernetes metrics.
Ensure that logs from the application are captured and visible in AWS CloudWatch.

Implement proper IAM roles and security policies for the Kubernetes nodes and pods, ensuring least privilege access.
Use Kubernetes secrets for sensitive data like database credentials or API keys.
