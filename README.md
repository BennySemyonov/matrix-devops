Exercise for Devops/MLops Engineer position on matrix.

 

The topics for the assignment:

Building a CI/CD Pipeline with Kubernetes, Docker, Python, and ClearML.

 

Task 1: Setting Up the Environment

 

- [x] 1. Create a GitHub repository for this exercise.
- https://github.com/BennySemyonov/matrix-devops

- [x] 2. Set up a Kubernetes cluster (locally using tools like Minikube or remotely using a cloud provider).
- GKE

- [x] 3. Install Docker on your local machine and ensure it's connected to your Kubernetes cluster.

 

Task 2: Containerizing a Python Application

 

- [x] 4. Write a simple Python web application using a framework of your choice.
- flask

- [x] 5. Create a Dockerfile to containerize the Python application.

- [x] 6. Build the Docker image with docker-compose and push it to Docker Hub or another container registry.
- matrix-devops/matrix-devops in europe-west1-docker.pkg.dev

 

Task 3: Implementing Continuous Integration

 

- [x] 7. Set up a CI/CD pipeline using a CI/CD tool of your choice (e.g., Jenkins, GitLab CI/CD, GitHub Actions).
- GitHub Actions

- [x] 8. Configure the CI pipeline to trigger when changes are pushed to your GitHub repository.

- [x] 9. In the CI pipeline, build and test the Python application within a Docker container.

- [ ] 10. Use ClearML to log and monitor the CI pipeline's performance and metrics.
 

Task 4: Deploying to Kubernetes

 

- [x] 11. Create Kubernetes deployment and service YAML files for your Python application.

- [x] 12. Configure your CI/CD pipeline to deploy the Docker container to your Kubernetes cluster after successful tests.

 

Task 5: Scaling and Monitoring

 

- [x] 13. Implement autoscaling for your Kubernetes deployment.

- [x] 14. Set up monitoring and logging for your Kubernetes cluster (e.g., using Prometheus and Grafana/Zabbix).
- Prometheus + Grafana
 

Task 6: Automating Rollbacks

 

- [x] 15. Implement automated rollbacks in your CI/CD pipeline based on predefined criteria (e.g., failed health checks).

 

Task 7: Documentation and Reporting

 

- [x] 16. Document the entire process, including setup, CI/CD pipeline configuration, and Kubernetes deployment.

- [x] 17. Create a report summarizing your approach, challenges faced, and improvements you would make.

 

Submission:

 

- [x] 18. Share the GitHub repository link with the instructions, code, and documentation.

 

This exercise covers various aspects of a DevOps engineer's role, including containerization, CI/CD pipeline setup, Kubernetes deployment, automation, and documentation. It also incorporates ClearML for monitoring and logging purposes.
