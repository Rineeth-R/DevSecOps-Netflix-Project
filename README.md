**DevSecOps Project - Netflix Clone on cloud using Jenkins**

![Screenshot 2025-06-14 094417](https://github.com/user-attachments/assets/183b0d6d-3957-476d-a2dc-ba66577beacb)



**Project Overview:**

Developed and deployed a Netflix-like streaming application on AWS using DevSecOps best practices. 

Implemented a CI/CD pipeline with Jenkins, integrated security tools (SonarQube, Trivy, OWASP Dependency-Check),
and set up monitoring with Prometheus and Grafana. Automated containerized deployments using Docker and Kubernetes.

**Key Responsibilities & Technologies Used**

**1. Cloud Infrastructure Setup & Deployment (AWS & Docker)** 

Provisioned AWS EC2 instance (Ubuntu 22.04) for hosting the application.
Installed and configured Docker for containerized deployment.
Built and deployed the application as a Docker container:
Pulled the application source code from GitHub.
Built Docker images and ran the application using Docker Compose.
Integrated TMDB API Key for fetching movie details.

**2. Security Implementation (DevSecOps)**
Installed and configured SonarQube to perform static code analysis for security vulnerabilities.
Scanned application dependencies using OWASP Dependency-Check.
Used Trivy for container image scanning to identify vulnerabilities.
Implemented SonarQube Quality Gate in Jenkins pipeline to enforce security standards.

**3. CI/CD Pipeline Automation (Jenkins)**

Installed Jenkins on the AWS EC2 instance.
Configured a Jenkins declarative pipeline for automating build, security scans, and deployment.
Integrated Docker plugins, Node.js, and Java (JDK 17) in Jenkins for seamless execution.
Implemented DockerHub authentication in Jenkins to push Docker images securely.
Configured Jenkins to trigger builds automatically on code commits.

**4. Monitoring & Logging (Prometheus & Grafana)**

Installed and configured Prometheus to monitor application performance.
Deployed Node Exporter for collecting system metrics.
Integrated Grafana to visualize logs and metrics from Prometheus.
Configured Prometheus monitoring for Jenkins CI/CD pipeline performance tracking.

**5. Kubernetes Deployment & Scaling**

Created a Kubernetes cluster with node groups for auto-scaling.
Deployed application containers in Kubernetes Pods for high availability.
Configured Helm to install Prometheus and monitor Kubernetes nodes.

**6. Notification & Alerts**

Set up email notifications in Jenkins for build failures.
Configured Prometheus AlertManager to notify on system anomalies.

**Key Achievements**

 A) Successfully deployed a Netflix Clone on AWS with an automated CI/CD pipeline.

 B) Implemented shift-left security by integrating SonarQube, Trivy, and OWASP Dependency-Check.

 C) Achieved 100% automation for build, security, and deployment using Jenkins.

 D) Improved system observability with real-time monitoring dashboards using Grafana.

 E) Ensured secure Docker image storage by integrating DockerHub authentication.

 F) Scaled application seamlessly using Kubernetes with Node Groups.


**Technical Stack & Tools**

**Cloud Platforms:** AWS

**CI/CD:** Jenkins, Git, GitHub Webhooks

**Containerization:** Docker, DockerHub, Kubernetes, Helm

**Security Tools:** SonarQube, OWASP Dependency-Check, Trivy

**Observebility - Monitoring & Logging:** Prometheus, Grafana, Node Exporter

**Programming & Scripting:** Shell Scripting, JavaScript, Node.js

**Database & APIs:** TMDB API

**Jenkins passed :-**

![Screenshot 2025-02-27 213928](https://github.com/user-attachments/assets/9d0d26cc-bfc1-4113-b703-21d05cc776ce)


![Screenshot 2025-02-27 214128](https://github.com/user-attachments/assets/046e6606-2089-41e9-a840-a8b617221219)




**SonarQube passed :-**

![Screenshot 2025-02-27 214858](https://github.com/user-attachments/assets/6ebf11ca-e98f-4463-9304-96a0f7d0e615)





**ARGOCD SYNCED :-**

![Screenshot 2025-02-27 214731](https://github.com/user-attachments/assets/d2306cf3-9caa-4ad8-8f69-50ee4de03c37)




**PROMETHEUS :-**

![Screenshot 2025-02-27 215224](https://github.com/user-attachments/assets/b8b9f988-dc83-4c36-a1ca-67836aa2acf9)



**NETFLIX PAGE :-**

![Screenshot 2025-02-27 215057](https://github.com/user-attachments/assets/38086f9b-3bcd-4976-8023-b56cc3304a12)



