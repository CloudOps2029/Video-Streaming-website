# Video-Streaming-website

Video Streaming Website Deployment on EKS with DevSecOps Pipeline

Project Overview
This project showcases a deployment of a video streaming website on an Amazon EKS (Elastic Kubernetes Service) cluster. The deployment follows DevSecOps principles, ensuring continuous integration and delivery (CI/CD) with a focus on security and code quality. The pipeline integrates SonarQube, Trivy, and Jenkins to automate code scanning, vulnerability assessment, and deployment.

Features
Video Streaming: A fully functional video streaming application hosted on EKS.
DevSecOps Pipeline: Security-integrated CI/CD pipeline ensuring code quality and vulnerability mitigation.
Tools Used:
SonarQube: Performs static code analysis to ensure code quality and detect issues early.
Trivy: Scans container images for vulnerabilities before deployment.
Jenkins: Automates the CI/CD pipeline, orchestrating build, test, and deployment stages.
Pipeline Stages
Code Analysis: SonarQube scans code for quality and security issues.
Container Image Scanning: Trivy checks container images for vulnerabilities.
Build and Deploy: Jenkins automates build and deployment to EKS, ensuring streamlined, secure, and efficient deployment.
Prerequisites
AWS account with EKS setup
Jenkins server with necessary plugins
SonarQube and Trivy configured and integrated with Jenkins
Getting Started
Clone the repository.
Configure Jenkins with the pipeline script.
Update the EKS configuration in your deployment files.
Run the pipeline to deploy the website.
Conclusion
This project demonstrates a secure, automated deployment of a cloud-native video streaming service on EKS, ensuring high code quality and security compliance.
