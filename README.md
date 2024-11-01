# Configuration Management and Deployment Automation with Ansible

This repository demonstrates my expertise in **Configuration Management** and **Deployment Automation** using **Ansible** to manage infrastructure and applications on both **AWS EC2** and **Kubernetes**. By working through these exercises, I've implemented automated solutions for complex deployment tasks, from provisioning AWS EC2 instances for web and database servers to deploying containerized applications in Kubernetes. Each Ansible playbook in this repository automates a specific aspect of application deployment, infrastructure setup, or configuration management.

---

## Project Overview

This project showcases:
1. **Automated Build and Deployment of Java Applications**: Automated build, deployment, and configuration of Java applications on remote servers using Ansible.
2. **Nexus Integration**: Artifact management with Nexus for secure storage and distribution of application builds.
3. **Jenkins Deployment**: Provisioning of Jenkins servers on both AWS EC2 instances and as Docker containers, supporting CI/CD on multiple OS environments.
4. **Web and Database Server Configuration**: Secure deployment and configuration of web and database servers within a private VPC on AWS.
5. **Kubernetes Deployment**: Containerized Java and MySQL applications deployed in Kubernetes, configured using Ansible for effortless orchestration.
6. **High-Availability MySQL Setup**: Deployment of MySQL with multiple replicas using Helm in Kubernetes for data redundancy and improved fault tolerance.

This project is part of my DevOps portfolio, showcasing hands-on skills in configuration management, infrastructure automation, and modern deployment strategies on cloud and container platforms.

---

## Exercises

### EXERCISE 1: Build & Deploy Java Artifact
Ansible automation of Java application build and deployment on a remote Ubuntu server. Key functionalities include:
- Building the Java Gradle application artifact.
- Stopping any existing application instances, removing old artifacts, and deploying the new build.
- Creating Linux user accounts for individual developers if they do not exist on the remote server.

### EXERCISE 2: Push Java Artifact to Nexus
Automated push of a Java build artifact to the Nexus repository. This playbook enables easy, local deployment and testing by developers, allowing them to push tested builds to Nexus for use by the team.

### EXERCISE 3: Install Jenkins on EC2
Ansible script to:
- Provision an EC2 server on AWS and install Jenkins.
- Configure Jenkins with Docker, Node.js, and npm for enhanced build capabilities.

### EXERCISE 4: Install Jenkins on Ubuntu
Extended the Jenkins installation playbook to support both AWS EC2 and Ubuntu environments using Ansible's conditional tasks.

### EXERCISE 5: Install Jenkins as a Docker Container
Deployed Jenkins as a Docker container with dedicated volumes, allowing Jenkins to run Docker commands internally. Ansible configuration for this setup includes:
- Dockerized Jenkins setup with persistent storage for Jenkins home and Docker socket.
- Port configurations to access Jenkins on a browser.

### EXERCISE 6: Web Server and Database Server Configuration
Deployed a web server and database server in an AWS VPC with secure configurations:
- Created a dedicated Ansible control server on AWS.
- Configured MySQL in a private subnet for data security, with NAT gateway for internet access when needed.
- Deployed a Java application on a separate EC2 instance with a public IP accessible from the browser.

### EXERCISE 7: Deploy Java-MySQL Application in Kubernetes
Automated deployment of a containerized Java and MySQL application on Kubernetes, leveraging Ansible for automation. Key configurations include:
- An nginx ingress controller for routing traffic to the Java application.
- Secrets and ConfigMaps for secure database connectivity.

### EXERCISE 8: Deploy MySQL Chart in Kubernetes
Improved MySQL's high availability by deploying a Helm chart with 3 replicas, ensuring fault tolerance and database reliability for the team.

---

## Technologies and Tools

- **Ansible**: Automation of configuration management and deployment tasks.
- **AWS EC2**: Scalable compute for deploying Jenkins, MySQL, and application servers.
- **AWS VPC**: Secure network configuration for EC2 instances.
- **Nexus**: Repository for managing and storing Java artifacts.
- **Jenkins**: CI/CD server deployment on various platforms.
- **Docker**: Containerization for deploying Jenkins as a portable, consistent environment.
- **Kubernetes**: Orchestration platform for managing Java and MySQL application deployments.
- **Helm**: Kubernetes package manager for deploying MySQL with high availability.

---

## Conclusion

This project demonstrates my ability to manage configuration and deployment tasks using Ansible, AWS, and Kubernetes, automating deployment workflows and creating flexible environments. This portfolio project is an example of effective Configuration Management, Continuous Integration, and Deployment Automation practices, showcasing valuable DevOps skills in modern cloud environments.


