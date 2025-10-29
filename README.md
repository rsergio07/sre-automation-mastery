# SRE Automation Mastery

## Introduction

SRE Automation Mastery is a comprehensive, hands-on course designed to teach Site Reliability Engineering automation practices using industry-standard tools. This course takes a practical approach to learning infrastructure automation, configuration management, and GitOps workflows through real-world scenarios and progressive exercises.

Unlike traditional courses that require expensive cloud infrastructure or complex setups, this program runs entirely on your local machine using open-source tools. You'll build a complete automated platform from the ground up, gaining practical experience with the same technologies used by leading technology companies to manage production infrastructure at scale.

## Why SRE Automation Matters

Modern infrastructure management requires automation to achieve reliability, scalability, and efficiency. Manual processes are error-prone, time-consuming, and don't scale. SRE automation principles enable teams to manage complex systems through code, ensuring consistency, repeatability, and rapid recovery from failures.

This course teaches you to automate infrastructure provisioning with Terraform, manage configuration with Ansible, deploy applications using Helm and Kubernetes, implement GitOps workflows with ArgoCD, and establish comprehensive monitoring and alerting systems. These skills are essential for anyone working in DevOps, platform engineering, or site reliability roles.

## What You'll Learn

The course progresses through seven modules, each building on concepts from previous sections. You'll start with Kubernetes package management using Helm, then move to infrastructure as code with Terraform. Configuration management with Ansible follows, including the AWX automation platform for web-based workflows. Advanced GitOps practices with ArgoCD teach you continuous delivery patterns. The monitoring and alerting module covers Prometheus, Grafana, and Alertmanager. Finally, you'll integrate all these tools in a comprehensive capstone project that simulates a production environment.

Each module contains multiple exercises with clear objectives, step-by-step instructions, and verification steps to ensure you've mastered the concepts. All exercises are designed to be completed in sequence, as later modules depend on knowledge from earlier ones.

## Course Structure

### Module 1: Helm
Learn Kubernetes package management and application deployment using Helm charts. Create, customize, and manage complex applications with templates and values.

### Module 2: Terraform
Master infrastructure as code by provisioning and managing Kubernetes resources declaratively. Understand state management, modules, and best practices for infrastructure automation.

### Module 3: Ansible
Automate configuration management and operational tasks using Ansible playbooks. Learn inventory management, roles, and idempotent automation patterns.

### Module 4: AWX
Deploy and use AWX, the open-source web-based interface for Ansible. Create job templates, manage credentials, and build automated workflows through a centralized platform.

### Module 5: GitOps Advanced
Implement GitOps workflows using ArgoCD for continuous delivery. Learn declarative application management, automated synchronization, and progressive deployment strategies.

### Module 6: Monitoring and Alerts
Build a complete observability stack with Prometheus for metrics collection, Grafana for visualization, and Alertmanager for intelligent alert routing and management.

### Module 7: Integration
Combine all learned technologies in a capstone project that simulates a real-world production environment. Design and implement an end-to-end automated platform with monitoring, deployment pipelines, and operational runbooks.

## Exercise Navigation

| Module | Exercise | Topic |
|--------|----------|-------|
| 1 - Helm | [Exercise 1](exercises/module1-helm/exercise1/) | Installing and deploying your first Helm chart |
| 1 - Helm | [Exercise 2](exercises/module1-helm/exercise2/) | Creating custom charts and working with values |
| 1 - Helm | [Exercise 3](exercises/module1-helm/exercise3/) | Chart dependencies and advanced templating |
| 2 - Terraform | [Exercise 1](exercises/module2-terraform/exercise1/) | Terraform basics and Kubernetes provider |
| 2 - Terraform | [Exercise 2](exercises/module2-terraform/exercise2/) | Managing state and creating modules |
| 2 - Terraform | [Exercise 3](exercises/module2-terraform/exercise3/) | Advanced resource management |
| 3 - Ansible | [Exercise 1](exercises/module3-ansible/exercise1/) | Ansible fundamentals and first playbook |
| 3 - Ansible | [Exercise 2](exercises/module3-ansible/exercise2/) | Roles, variables, and inventory management |
| 3 - Ansible | [Exercise 3](exercises/module3-ansible/exercise3/) | Complex automation workflows |
| 4 - AWX | [Exercise 1](exercises/module4-awx/exercise1/) | Installing and configuring AWX |
| 4 - AWX | [Exercise 2](exercises/module4-awx/exercise2/) | Creating job templates and workflows |
| 4 - AWX | [Exercise 3](exercises/module4-awx/exercise3/) | Integration with external systems |
| 5 - GitOps | [Exercise 1](exercises/module5-gitops-advanced/exercise1/) | ArgoCD installation and basic concepts |
| 5 - GitOps | [Exercise 2](exercises/module5-gitops-advanced/exercise2/) | Application deployment patterns |
| 5 - GitOps | [Exercise 3](exercises/module5-gitops-advanced/exercise3/) | Multi-environment strategies |
| 6 - Alerts | [Exercise 1](exercises/module6-alerts/exercise1/) | Prometheus and metrics collection |
| 6 - Alerts | [Exercise 2](exercises/module6-alerts/exercise2/) | Grafana dashboards and Alertmanager |
| 7 - Integration | [Exercise 1](exercises/module7-integration/exercise1/) | Connecting the automation pipeline |
| 7 - Integration | [Capstone](exercises/module7-integration/capstone/) | Final integrated project |

## Getting Started

Before beginning the exercises, you'll need to set up your local environment. This course uses Colima for container runtime, Minikube for a local Kubernetes cluster, and various CLI tools including kubectl, Helm, Terraform, and Ansible.

Detailed setup instructions are available in [PREREQUISITES.md](PREREQUISITES.md), which includes an automated installation script for macOS. The setup script installs all required tools and verifies your system meets the minimum requirements. A cleanup script is also provided if you need to reset your environment.

Once your environment is ready, start with Module 1, Exercise 1 and progress sequentially through the course. Each exercise README contains learning objectives, detailed steps, and verification commands to confirm successful completion.

## Projects Directory

The `projects/` directory is your workspace for experimenting with the concepts learned in the exercises. Use this area to build custom configurations, test different approaches, or develop your own automation solutions beyond the structured exercises.

## Prerequisites

This course requires basic command-line proficiency, familiarity with Git, and understanding of YAML syntax. Prior Kubernetes experience is helpful but not mandatory, as fundamental concepts are introduced as needed. Complete prerequisites and system requirements are detailed in [PREREQUISITES.md](PREREQUISITES.md).

## Contributing

Contributions are welcome and encouraged. Whether you find errors, want to improve existing exercises, or have ideas for new content, please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License. See [LICENSE.md](LICENSE.md) for details.