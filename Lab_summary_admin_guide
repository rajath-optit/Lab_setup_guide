# Lab Environment Documentation

## Table of Contents

1. [Proxmox Virtual Environment (VE)](#proxmox-virtual-environment-ve)
   - Overview
   - Access Details
   - Version and Release Date
   - Service Nodes
2. [Lab Environment Details](#lab-environment-details)
   - Jenkins Cluster
     - Services and IP Addresses
   - Kubernetes Cluster
     - Nodes and IP Addresses
   - Virtual Machine Templates
3. [Comprehensive Lab Environment Configuration Guide](#comprehensive-lab-environment-configuration-guide)
   - Overview
   - Version Control
     - Git
   - Build and Development Tools
     - Maven
     - Java
     - Node.js and npm
     - .NET
     - Python3
     - boto3
   - Continuous Integration and Delivery (CI/CD)
     - Jenkins
     - Plugins Installed
   - Containerization and Orchestration
     - Docker
     - Docker Compose
     - Kubernetes
     - k9s
   - Infrastructure as Code (IaC)
     - Terraform
   - Monitoring and Visualization
     - Prometheus
     - Grafana
     - EFK Stack
   - Additional Tools
     - Helm
     - Argo CD
     - SonarQube
4. [Application Repositories for Practice](#application-repositories-for-practice)
   - Gradle Basic Application
     - Repository and Description
   - Python Flask Application
     - Repository and Description
   - Recipe Management System
     - Repository and Description
   - Additional Repositories
     - Node Port Application
     - Kompose + StatefulSet Application
     - Ingress Application
5. [Lab DevOps Tools](#lab-devops-tools)
   - Maven
     - Definition and Lab Installation
   - Docker
     - Definition and Lab Installation
   - Docker Compose
     - Definition and Lab Installation
   - Kubernetes
     - Definition and Lab Installation
     - Cluster Configuration
     - Additional Information
   - Helm
     - Definition and Lab Installation
   - Jenkins
     - Definition and Introduction
     - Jenkins Cluster Configuration
     - Lab Jenkins Environment
6. [Argo CD](#argo-cd)
   - Definition and Introduction
   - Lab Installation
   - Access Details
7. [Grafana](#grafana)
   - Definition and Introduction
   - Lab Installation
   - Access Details
8. [EFK Stack (Elasticsearch, Fluentd, Kibana)](#efk-stack-elasticsearch-fluentd-kibana)
   - Definition and Introduction
   - Lab Installation
   - Additional Information
9. [Updates](#updates)

## Proxmox Virtual Environment (VE)

### Overview

Proxmox VE is an open-source server virtualization management platform that combines Kernel-based Virtual Machine (KVM) and Linux Containers (LXC). It provides a web-based interface for managing virtual machines, containers, storage, and networking. Proxmox VE supports high availability clusters, backup and restore, and live migration. It is widely used for its powerful features and ease of integration into existing IT infrastructure.

### Access Details

- **URL:** [Proxmox VE](https://10.10.30.20:8006/v1:0:=qemu%2F111:4:::::21::)
- **Username:** (Your email address)
- **Password:** Optit@123

### Version and Release Date

- **Version:** 7.4-3
- **Release Date:** April 19, 2023

### Service Nodes

| Service             | IP Address     |
|---------------------|----------------|
| Jenkins             | 10.10.30.77    |
| Jenkins Slave Node  | 10.10.30.70    |
| PE                  | 10.10.30.78    |
| Kubernetes Master   | 10.10.30.87    |
| Kubernetes Node 1   | 10.10.30.88    |
| Kubernetes Node 2   | 10.10.30.89    |

### Virtual Machine Templates

| ID  | Description                     |
|-----|---------------------------------|
| 117 | Ubuntu 20.04 Template            |
| 999 | Ubuntu 22.04 Template            |
| 111 | Platform Engineering VM          |

## Lab Environment Details

### Jenkins Cluster

- **Services and IP Addresses:**
  - Jenkins: 10.10.30.77
  - Jenkins Slave Node: 10.10.30.70
  - PE: 10.10.30.78

### Kubernetes Cluster

- **Nodes and IP Addresses:**
  - K8s Master Node: 10.10.30.87
  - K8s Node 1: 10.10.30.88
  - K8s Node 2: 10.10.30.89

### Virtual Machine Templates

- **Ubuntu Template ID:** 117, 999
- **Platform Engineering VM ID:** 111

## Comprehensive Lab Environment Configuration Guide

### Overview

The lab environment is configured with various tools and technologies to support development, continuous integration, and deployment. The setup includes version control systems, build tools, CI/CD tools, containerization, monitoring, and more.

### Version Control

- **Git:** 2.35.1

### Build and Development Tools

- **Maven:** 3.8.5
- **Java:** 11 (with Java 17 also installed)
- **Node.js and npm**
- **.NET**
- **Python3**
- **boto3**

### Continuous Integration and Delivery (CI/CD)

- **Jenkins:** 2.331
- **Plugins Installed:** [List specific Jenkins plugins if applicable]

### Containerization and Orchestration

- **Docker**
  - **Version:** latest (or specify a particular version if needed)
- **Docker Compose**
- **Kubernetes**
- **k9s**

### Infrastructure as Code (IaC)

- **Terraform:** 1.1.0

### Monitoring and Visualization

- **Prometheus**
- **Grafana**
- **EFK Stack**
  - **Components:**
    - Elasticsearch
    - Fluentd
    - Kibana

### Additional Tools

- **Helm**
- **Argo CD**
- **SonarQube:** 8.9.4-community

## Application Repositories for Practice

### Gradle Basic Application

- **Description:** A simple service built using Gradle for testing various tools.
- **Repository:** [Gradle Sample Service]

### Python Flask Application

- **Description:** Built using Python and Flask, with microservice communication using RabbitMQ.
- **Repository:** [Python Microservice Example]

### Recipe Management System

- **Description:** An MVC web application for managing food recipes, integrated with MySQL.
- **Repository:** [Spring MVC Example]

### Additional Repositories

- **Node Port Application**
- **Kompose + StatefulSet Application**
- **Ingress Application**

## Lab DevOps Tools

### Maven

- **Definition and Introduction**
- **Lab Installation**

### Docker

- **Definition and Introduction**
- **Lab Installation**

### Docker Compose

- **Definition and Introduction**
- **Lab Installation**

### Kubernetes

- **Definition and Introduction**
- **Lab Installation**
- **Cluster Configuration**
  - **Nodes and IP Addresses:**
    - K8s Master Node: 10.10.30.87
    - K8s Node 1: 10.10.30.88
    - K8s Node 2: 10.10.30.89
- **Additional Information:**
  - K9s Integration
  - Application Monitoring
  - Resource Management
  - Namespace Management
  - Ingress and Networking
  - Persistent Storage

### Helm

- **Definition and Introduction**
- **Lab Installation**

### Jenkins

- **Definition and Introduction**
- **Jenkins Cluster Configuration**
  - **URL:** http://10.10.30.77:9090
  - **Username:** your name
  - **Password:** provided separately to each user
- **Lab Jenkins Environment**

## Argo CD

- **Definition and Introduction**
- **Lab Installation**
- **Access Details**
  - **URL:** http://argocd.10-10-30-87.sslip.io
  - **Username:** admin
  - **Password:** Optit@123

## Grafana

- **Definition and Introduction**
- **Lab Installation**
- **Access Details**
  - **URL:** http://grafana.10-10-30-87.sslip.io
  - **Username:** (Your email address)
  - **Password:** Optit@123

## EFK Stack (Elasticsearch, Fluentd, Kibana)

- **Definition and Introduction**
- **Lab Installation**

## Updates

Updates will be added below this

not for everyone:
https://optit2022-my.sharepoint.com/:w:/g/personal/rajath_h_optit_in/ESDV2dXVBTdGq3vU3x1m2IsBYSy_Wo0XB73dj_T95O0wsQ?e=SFaAJw
