# DevOps Dynamo Project

Welcome to the DevOps Dynamo Project Overview! In this document, I will provide a summary of a comprehensive DevOps project I have recently completed. This project encompasses various tools and practices to enhance the software development, deployment, and monitoring processes.

## Project Scope

The primary objective of this project was to establish a robust DevOps pipeline while automating infrastructure provisioning and optimizing development workflows. Below, I will outline the key components and highlights of this project.

### Infrastructure and Environment

- **Terraform for Infrastructure**: Leveraged Terraform to automate the setup of cloud resources, networks, and security configurations.

- **Jenkins Controller**: Created a Jenkins controller instance to centralize CI/CD pipelines management.

- **Build Node**: Provisioned a dedicated build node to build and test application code.

- **Ansible for Configuration**: Utilized Ansible for automated configuration management tasks across the infrastructure.

### CI/CD Pipeline Automation

- **Jenkins and Ansible Integration**: Configured Jenkins controller and build node using Ansible playbooks to ensure consistent environments.

- **Jenkins Pipeline Setup**: Defined Jenkins pipeline jobs for automating the build, test, and deployment processes.

- **Jenkinsfile Creation**: Crafted Jenkinsfiles from scratch to define customized pipeline stages.

- **Multibranch Pipeline**: Implemented a multibranch pipeline for continuous integration across various code branches.

- **GitHub Webhook Integration**: Enabled GitHub webhooks to trigger automated builds and deployments upon code changes.

### Code Quality and Security

- **SonarQube Integration**: Integrated SonarQube for code quality analysis and adherence to coding standards.

- **Sonar Scanner Execution**: Executed the SonarQube scanner to assess code quality and security.

- **Custom SonarQube Rules**: Defined custom rules and gates within SonarQube to enforce coding standards and security practices.

- **SonarQube Callbacks**: Set up callback rules to notify development teams of code quality issues.

### Artifact Management

- **JFrog Artifactory Configuration**: Established JFrog Artifactory to store Docker images and other artifacts.

- **Docker Containerization**: Created Dockerfiles to containerize application components.

- **Artifactory for Docker Images**: Stored Docker images on JFrog Artifactory for version control and distribution.

### Kubernetes Deployment

- **Provisioning Kubernetes Objects**: Deployed Kubernetes objects such as pods, services, and deployments to facilitate application deployment.

- **Helm Chart Deployment**: Utilized Helm charts for simplified management of Kubernetes deployments and releases.

### Monitoring and Observability

- **Prometheus and Grafana Setup**: Configured Prometheus and Grafana using Helm charts to monitor the Kubernetes cluster and application performance.

- **Kubernetes Cluster Monitoring**: Collected and visualized metrics from the Kubernetes cluster using Prometheus and Grafana dashboards.

## Project Visuals

Here are some visual representations and screenshots of the project components:

1. **Infrastructure Diagram**
   ![Infrastructure Diagram](![Alt text](<images/Screenshot 2023-09-01 at 8.57.29 PM.png>) ![Alt text](<images/Screenshot 2023-09-01 at 9.00.33 PM.png>) ![Alt text](<images/Screenshot 2023-09-01 at 9.28.02 PM.png>))

2. **CI/CD Pipeline Flow**
   ![CI/CD Pipeline Flow](images/cicd_flow.png)

3. **SonarQube Dashboard**
   ![SonarQube Dashboard](images/sonarqube_dashboard.png)

4. **Kubernetes Cluster Overview**
   ![Kubernetes Cluster Overview](images/kubernetes_cluster.png)

5. **Prometheus Metrics**
   ![Prometheus Metrics](images/prometheus_metrics.png)

## Conclusion

This DevOps project encompasses an array of tools and technologies to automate and streamline development, deployment, and monitoring. The integration of Jenkins, Terraform, Ansible, SonarQube, JFrog Artifactory, Kubernetes, Prometheus, and Grafana has resulted in a powerful and scalable DevOps pipeline.

