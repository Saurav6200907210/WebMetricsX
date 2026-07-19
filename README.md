# 🚀 WebMetricsX

<div align="center">

# 🌐 Enterprise Website Monitoring Platform

### 📊 Real-Time Website Monitoring • ⚡ DevOps Automation • ☁️ Cloud Native • 🚀 CI/CD Deployment

<p align="center">

![React](https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=white)

![Node](https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws)

</p>

<img src="public/banner.png"/>

</div>

---

# 📖 About WebMetricsX

**WebMetricsX** is a **production-ready enterprise website monitoring platform** designed to continuously monitor websites, analyze SEO performance, measure response time, detect failures, and visualize live metrics using modern DevOps technologies.

Unlike basic monitoring tools, WebMetricsX integrates a **complete DevOps ecosystem** including:

- 🚀 Jenkins CI/CD
- 🐳 Docker
- ☸ Kubernetes
- ☁ AWS EC2
- 🏗 Terraform
- 🤖 Ansible
- 📊 Prometheus
- 📈 Grafana

to deliver an automated, scalable, cloud-native monitoring solution.

---

# ✨ Key Features

## 🌍 Website Monitoring

- Live Website Status
- HTTP Status Monitoring
- DNS Lookup
- SSL Validation
- TTFB Analysis
- Response Time Tracking
- Availability Monitoring

---

## 📊 Analytics

- Performance Monitoring
- Website Speed
- Core Web Vitals
- SEO Analysis
- Performance Score
- Accessibility Report
- Best Practices Audit

---

## 📈 Dashboard

- Beautiful Charts
- Live Statistics
- Auto Refresh (Every 5 Seconds)
- Interactive UI
- Responsive Design

---

## 📄 Reporting

- PDF Report Export
- Website Summary
- SEO Summary
- Performance Report

---

## ⚙ DevOps

- Jenkins Pipeline
- Docker Containerization
- DockerHub Image Registry
- Kubernetes Deployment
- Terraform Infrastructure
- Ansible Automation
- Prometheus Monitoring
- Grafana Dashboards

---

# 🏗 High Level Architecture

```mermaid
flowchart LR

User["👨‍💻 User"]

React["⚛ React Frontend"]

Node["🚀 Node.js API"]

Monitor["📊 Monitoring Engine"]

API["🌍 Website"]

SEO["🔍 SEO APIs"]

Charts["📈 Dashboard"]

PDF["📄 PDF Report"]

User --> React

React --> Node

Node --> Monitor

Monitor --> API

Monitor --> SEO

Monitor --> Charts

Charts --> PDF

style User fill:#2563eb,color:#fff,stroke:#000
style React fill:#06b6d4,color:#fff,stroke:#000
style Node fill:#22c55e,color:#fff,stroke:#000
style Monitor fill:#9333ea,color:#fff,stroke:#000
style API fill:#f97316,color:#fff,stroke:#000
style SEO fill:#dc2626,color:#fff,stroke:#000
style Charts fill:#0891b2,color:#fff,stroke:#000
style PDF fill:#0f766e,color:#fff,stroke:#000
```

---

# 🏢 Enterprise System Architecture

```mermaid
flowchart TD

Client["🌐 Client Browser"]

Cloudflare["☁ Cloudflare CDN"]

Frontend["⚛ React Application"]

Backend["🚀 Express Server"]

Engine["📊 Monitoring Engine"]

DNS["🌍 DNS Lookup"]

SSL["🔒 SSL Check"]

Performance["⚡ Performance Test"]

SEO["🔍 SEO Audit"]

Database["💾 Report Storage"]

Charts["📈 Dashboard"]

PDF["📄 Export Report"]

Client --> Cloudflare

Cloudflare --> Frontend

Frontend --> Backend

Backend --> Engine

Engine --> DNS

Engine --> SSL

Engine --> Performance

Engine --> SEO

Engine --> Database

Database --> Charts

Charts --> PDF

style Client fill:#2563eb,color:#fff
style Cloudflare fill:#F38020,color:#fff
style Frontend fill:#06b6d4,color:#fff
style Backend fill:#16a34a,color:#fff
style Engine fill:#9333ea,color:#fff
style DNS fill:#ea580c,color:#fff
style SSL fill:#0891b2,color:#fff
style Performance fill:#dc2626,color:#fff
style SEO fill:#0f766e,color:#fff
style Database fill:#6366f1,color:#fff
style Charts fill:#ca8a04,color:#fff
style PDF fill:#15803d,color:#fff
```

---

# 🔄 Monitoring Workflow

```mermaid
flowchart LR

Start["🌐 User Enters URL"]

Validate["✔ URL Validation"]

Request["📡 HTTP Request"]

Analyze["⚡ Performance Analysis"]

SEO["🔍 SEO Analysis"]

Store["💾 Generate Report"]

Dashboard["📊 Live Dashboard"]

PDF["📄 PDF Export"]

Start --> Validate

Validate --> Request

Request --> Analyze

Analyze --> SEO

SEO --> Store

Store --> Dashboard

Dashboard --> PDF

style Start fill:#2563eb,color:#fff
style Validate fill:#16a34a,color:#fff
style Request fill:#dc2626,color:#fff
style Analyze fill:#9333ea,color:#fff
style SEO fill:#0891b2,color:#fff
style Store fill:#f97316,color:#fff
style Dashboard fill:#0f766e,color:#fff
style PDF fill:#7c3aed,color:#fff
```

---

# 📸 Application Preview

## 🖥 Dashboard

![Dashboard](public/dashboard.png)

---

## 📊 Performance

![Performance](public/performance.png)

---

## 🔍 SEO Analysis

![SEO](public/seo.png)

---

## 📄 PDF Report

![PDF](public/exportedpdf1.png)

![PDF](public/exportedpdf2.png)

---

---

# 🚀 DevOps Architecture

WebMetricsX follows a **production-ready DevOps workflow** where every code change is automatically built, tested, containerized, deployed, and monitored.

## 🔥 DevOps Workflow

```mermaid
flowchart LR

Developer["👨‍💻 Developer"]

Git["📂 Git"]

GitHub["🐙 GitHub"]

Webhook["🔔 GitHub Webhook"]

Jenkins["⚙ Jenkins Pipeline"]

Docker["🐳 Docker Build"]

DockerHub["📦 DockerHub"]

Kubernetes["☸ Kubernetes"]

Service["🌐 Kubernetes Service"]

Users["👥 End Users"]

Developer --> Git

Git --> GitHub

GitHub --> Webhook

Webhook --> Jenkins

Jenkins --> Docker

Docker --> DockerHub

DockerHub --> Kubernetes

Kubernetes --> Service

Service --> Users

style Developer fill:#2563eb,color:#fff
style Git fill:#f97316,color:#fff
style GitHub fill:#000000,color:#fff
style Webhook fill:#06b6d4,color:#fff
style Jenkins fill:#D24939,color:#fff
style Docker fill:#2496ED,color:#fff
style DockerHub fill:#0db7ed,color:#fff
style Kubernetes fill:#326CE5,color:#fff
style Service fill:#16a34a,color:#fff
style Users fill:#9333ea,color:#fff
```

---

# ⚙ Continuous Integration & Continuous Deployment

Every push to GitHub automatically triggers a Jenkins pipeline that builds, tests, packages, and deploys the application.

## 🔄 CI/CD Pipeline

```mermaid
flowchart LR

Push["📤 Git Push"]

GitHub["🐙 GitHub"]

Webhook["🔔 Webhook"]

Jenkins["⚙ Jenkins"]

Checkout["📥 Checkout Code"]

Build["🔨 Build"]

Test["✅ Test"]

Docker["🐳 Docker Build"]

PushImage["📦 Push Docker Image"]

Deploy["☸ Kubernetes Deploy"]

Production["🚀 Live Production"]

Push --> GitHub

GitHub --> Webhook

Webhook --> Jenkins

Jenkins --> Checkout

Checkout --> Build

Build --> Test

Test --> Docker

Docker --> PushImage

PushImage --> Deploy

Deploy --> Production

style Push fill:#2563eb,color:#fff
style GitHub fill:#000000,color:#fff
style Jenkins fill:#D24939,color:#fff
style Build fill:#16a34a,color:#fff
style Test fill:#22c55e,color:#fff
style Docker fill:#2496ED,color:#fff
style PushImage fill:#0ea5e9,color:#fff
style Deploy fill:#326CE5,color:#fff
style Production fill:#9333ea,color:#fff
```

---

# 🐳 Docker Architecture

Docker is used to package the complete application into portable containers.

## Container Architecture

```mermaid
flowchart TB

Source["💻 Source Code"]

Dockerfile["📄 Dockerfile"]

Image["🐳 Docker Image"]

Registry["📦 DockerHub"]

Container["🚀 Running Container"]

Source --> Dockerfile

Dockerfile --> Image

Image --> Registry

Registry --> Container

style Source fill:#2563eb,color:#fff
style Dockerfile fill:#16a34a,color:#fff
style Image fill:#2496ED,color:#fff
style Registry fill:#0ea5e9,color:#fff
style Container fill:#9333ea,color:#fff
```

### 📸 Docker Build

![Docker](public/images.png)

---

### 📸 DockerHub Images

![DockerHub](public/dockerhub.png)

---

# ☸ Kubernetes Deployment

Kubernetes manages application deployment, scaling, and availability.

## Kubernetes Architecture

```mermaid
flowchart TB

Users["👥 Users"]

Ingress["🌐 Ingress"]

Service["⚡ Service"]

Deployment["📦 Deployment"]

Pod1["🟦 Pod 1"]

Pod2["🟩 Pod 2"]

Pod3["🟨 Pod 3"]

Users --> Ingress

Ingress --> Service

Service --> Deployment

Deployment --> Pod1

Deployment --> Pod2

Deployment --> Pod3

style Users fill:#2563eb,color:#fff
style Ingress fill:#16a34a,color:#fff
style Service fill:#22c55e,color:#fff
style Deployment fill:#326CE5,color:#fff
style Pod1 fill:#9333ea,color:#fff
style Pod2 fill:#9333ea,color:#fff
style Pod3 fill:#9333ea,color:#fff
```

### Kubernetes Features

- ReplicaSets
- Rolling Updates
- Self-Healing Pods
- Auto Scheduling
- Service Discovery
- Load Balancing
- Horizontal Scaling

---

### 📸 Deployments

![Deployment](public/deployments.png)

---

### 📸 Services

![Services](public/service.png)

---

# ☁ AWS Infrastructure

The application is hosted on AWS EC2 using Infrastructure as Code.

```mermaid
flowchart LR

Terraform["🏗 Terraform"]

AWS["☁ AWS"]

VPC["🌐 VPC"]

EC2["🖥 EC2"]

Docker["🐳 Docker"]

Kubernetes["☸ Kubernetes"]

Terraform --> AWS

AWS --> VPC

VPC --> EC2

EC2 --> Docker

Docker --> Kubernetes

style Terraform fill:#7B42BC,color:#fff
style AWS fill:#FF9900,color:#fff
style VPC fill:#16a34a,color:#fff
style EC2 fill:#2563eb,color:#fff
style Docker fill:#2496ED,color:#fff
style Kubernetes fill:#326CE5,color:#fff
```

---

# 🏗 Infrastructure as Code (Terraform)

Terraform provisions cloud infrastructure automatically.

## Terraform Workflow

```mermaid
flowchart LR

Code["📝 Terraform Code"]

Init["terraform init"]

Plan["terraform plan"]

Apply["terraform apply"]

AWS["☁ AWS Resources"]

EC2["🖥 EC2"]

Code --> Init

Init --> Plan

Plan --> Apply

Apply --> AWS

AWS --> EC2

style Code fill:#7B42BC,color:#fff
style Init fill:#2563eb,color:#fff
style Plan fill:#16a34a,color:#fff
style Apply fill:#9333ea,color:#fff
style AWS fill:#FF9900,color:#fff
style EC2 fill:#22c55e,color:#fff
```

### 📸 Terraform Output

![Terraform](public/terraform.png)

---

# 🤖 Configuration Management (Ansible)

Ansible automates complete server provisioning.

```mermaid
flowchart LR

Inventory["📋 Inventory"]

Playbook["📄 Playbook"]

SSH["🔐 SSH"]

Target["🖥 EC2"]

Docker["🐳 Docker"]

Jenkins["⚙ Jenkins"]

Kubectl["☸ kubectl"]

Inventory --> Playbook

Playbook --> SSH

SSH --> Target

Target --> Docker

Target --> Jenkins

Target --> Kubectl

style Inventory fill:#2563eb,color:#fff
style Playbook fill:#dc2626,color:#fff
style SSH fill:#0891b2,color:#fff
style Target fill:#16a34a,color:#fff
style Docker fill:#2496ED,color:#fff
style Jenkins fill:#D24939,color:#fff
style Kubectl fill:#326CE5,color:#fff
```

### Automated Installation

- Docker Engine
- Jenkins
- kubectl
- Git
- Required Packages
- User Permissions

### 📸 Ansible Execution

![Ansible](public/Ansible.png)

---

---

# 📊 Monitoring & Observability

WebMetricsX is equipped with a complete **cloud-native monitoring stack** to provide real-time visibility into application health, infrastructure performance, and Kubernetes workloads.

The monitoring stack collects metrics from containers, Kubernetes resources, and system components, then visualizes them through interactive Grafana dashboards.

---

# 🏗 Monitoring Architecture

```mermaid
flowchart LR

Users["👨‍💻 Users"]

Browser["🌐 Browser"]

Application["🚀 WebMetricsX"]

Exporter["📡 Metrics Exporter"]

Prometheus["📊 Prometheus"]

Grafana["📈 Grafana"]

Alerts["🚨 Alert Manager"]

Admin["👨‍💼 DevOps Engineer"]

Users --> Browser

Browser --> Application

Application --> Exporter

Exporter --> Prometheus

Prometheus --> Grafana

Prometheus --> Alerts

Grafana --> Admin

Alerts --> Admin

style Users fill:#2563eb,color:#fff
style Browser fill:#16a34a,color:#fff
style Application fill:#9333ea,color:#fff
style Exporter fill:#22c55e,color:#fff
style Prometheus fill:#E6522C,color:#fff
style Grafana fill:#F46800,color:#fff
style Alerts fill:#dc2626,color:#fff
style Admin fill:#0891b2,color:#fff
```

---

# 📊 Prometheus Metrics Collection

```mermaid
flowchart TB

Kubernetes["☸ Kubernetes"]

Pods["📦 Pods"]

NodeExporter["🖥 Node Exporter"]

cAdvisor["📊 cAdvisor"]

Prometheus["📈 Prometheus"]

Kubernetes --> Pods

Pods --> cAdvisor

NodeExporter --> Prometheus

cAdvisor --> Prometheus

style Kubernetes fill:#326CE5,color:#fff
style Pods fill:#9333ea,color:#fff
style NodeExporter fill:#16a34a,color:#fff
style cAdvisor fill:#2563eb,color:#fff
style Prometheus fill:#E6522C,color:#fff
```

---

# 📈 Grafana Dashboard

Grafana provides rich dashboards for visualizing:

- CPU Usage
- Memory Utilization
- Network Traffic
- Pod Status
- Container Health
- HTTP Requests
- Response Time
- Kubernetes Metrics

### 📸 Grafana Dashboard

> Replace with your Grafana dashboard screenshot.

```text
public/grafana-dashboard.png
```

---

# 📊 Prometheus UI

Prometheus continuously scrapes metrics from exporters and Kubernetes resources.

### 📸 Prometheus UI

> Replace with your Prometheus UI screenshot.

```text
public/prometheus.png
```

---

# 📂 Project Structure

```text
WebMetricsX
│
├── frontend
│   ├── public
│   ├── src
│   ├── components
│   ├── pages
│   ├── hooks
│   └── utils
│
├── backend
│   ├── controllers
│   ├── routes
│   ├── middleware
│   ├── services
│   ├── config
│   └── server.js
│
├── docker
│   ├── Dockerfile
│   └── docker-compose.yml
│
├── kubernetes
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── ingress.yaml
│   └── namespace.yaml
│
├── terraform
│   ├── main.tf
│   ├── variables.tf
│   └── outputs.tf
│
├── ansible
│   ├── inventory
│   ├── playbook.yml
│   └── roles
│
├── jenkins
│   └── Jenkinsfile
│
├── monitoring
│   ├── prometheus.yml
│   └── grafana
│
└── README.md
```

---

# 🛠 Tech Stack

## Frontend

- React.js
- Tailwind CSS
- Chart.js
- Axios

---

## Backend

- Node.js
- Express.js
- REST API

---

## DevOps

- Docker
- Docker Compose
- Jenkins
- GitHub Actions *(Optional)*
- Kubernetes
- Terraform
- Ansible
- AWS EC2

---

## Monitoring

- Prometheus
- Grafana
- Node Exporter
- cAdvisor

---

## Version Control

- Git
- GitHub

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Saurav6200907210/webmetrics-e2e-devops-project.git
```

Move into the project directory:

```bash
cd webmetrics-e2e-devops-project
```

Install dependencies:

```bash
npm install
```

Run the frontend:

```bash
npm run dev
```

Run the backend:

```bash
npm start
```

---

# 🐳 Docker

Build the image:

```bash
docker build -t webmetrics .
```

Run the container:

```bash
docker run -p 3000:3000 webmetrics
```

---

# ☸ Kubernetes

Deploy all resources:

```bash
kubectl apply -f kubernetes/
```

Check Pods:

```bash
kubectl get pods
```

Check Services:

```bash
kubectl get svc
```

---

# ⚙ Terraform

Initialize Terraform:

```bash
terraform init
```

Create execution plan:

```bash
terraform plan
```

Provision infrastructure:

```bash
terraform apply
```

---

# 🤖 Ansible

Execute the playbook:

```bash
ansible-playbook playbook.yml
```

---

# 🎯 Project Highlights

- ✅ Real-Time Website Monitoring
- ✅ SEO Analysis
- ✅ Performance Metrics
- ✅ Automated PDF Reports
- ✅ Jenkins CI/CD
- ✅ Dockerized Application
- ✅ Kubernetes Deployment
- ✅ Terraform Infrastructure
- ✅ Ansible Automation
- ✅ AWS Deployment
- ✅ Prometheus Monitoring
- ✅ Grafana Dashboards
- ✅ Production-Ready Architecture

---

# 🚀 Future Enhancements

- 🔐 User Authentication
- 🌍 Multi-Region Deployment
- 📱 Mobile Dashboard
- 🤖 AI-Based Performance Insights
- 🔔 Slack & Email Alerts
- 📩 Webhook Notifications
- 🌐 Multi-Cloud Deployment
- 📦 Helm Charts
- ⚡ ArgoCD GitOps Deployment
- 📊 Loki Log Aggregation

---

# 💼 Resume Highlights

- Designed and developed a **production-ready full-stack website monitoring platform**.
- Built an **automated CI/CD pipeline using Jenkins**.
- Containerized the application using **Docker**.
- Deployed workloads on **Kubernetes**.
- Provisioned AWS infrastructure using **Terraform**.
- Automated server configuration using **Ansible**.
- Implemented **Prometheus + Grafana** for monitoring and observability.
- Followed cloud-native DevOps best practices for scalable deployments.

---

# 📌 Release

### 🚀 Version 1.0.0

Initial enterprise release featuring:

- Website Monitoring
- DevOps Automation
- CI/CD Pipeline
- Kubernetes Deployment
- Monitoring Stack
- Infrastructure Automation

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push your branch
5. Open a Pull Request

---

# ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub.

It helps the project reach more developers and motivates future improvements.

---

# 📜 License

This project is licensed under the **MIT License**.

---

<div align="center">

## 🚀 Built with ❤️ by Saurav Kumar

### Full Stack Developer • DevOps Engineer • Cloud Enthusiast

**If you like this project, don't forget to ⭐ Star the repository!**

</div>
