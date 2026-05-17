<div align="center">

# Hey there, I'm Jesús 👋

**IT Systems & Networks Graduate · Aspiring Appian Associate Developer · DevOps Enthusiast**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jesuscmoramesa/)

</div>

---

## 👨‍💻 About Me

I hold a **Higher Technician in Computer Network Systems Management (ASIR)**, graduated with distinction and currently awaiting confirmation of Honours (Matrícula de Honor). The programme gave me a solid foundation in networking, systems, and infrastructure management.

Right now, I'm deep into **Appian** — working towards my **Appian Associate Developer certification** with STEMDO and exploring the world of low-code enterprise automation. At the same time, my passion for **DevOps** keeps growing: I love everything around infrastructure as code, containers, and cloud deployments.

This repository is where I'll be sharing projects focused on **deployment pipelines, infrastructure automation, and cloud architecture** — so feel free to explore and give feedback!

- 🎓 **Higher Technician in Computer Network Systems Management (ASIR)**, Honours pending 🤞 
- 📚 **Currently training** for the Appian Associate Developer certification
- ☁️ **Passionate about** DevOps, cloud infrastructure and automation
- 🚀 **Building** projects around deployment, containers and IaC

---

## 🛠️ Tech Stack & Tools

<div align="center">

### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

### 💻 Languages & Databases
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### 🔧 Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Appian](https://img.shields.io/badge/Appian-E84646?style=for-the-badge&logo=appian&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com/?user=JesusCMM13&theme=tokyonight&hide_border=true" height="165"/>

![Profile views](https://komarev.com/ghpvc/?username=JesusCMM13&color=0e75b6&style=flat&label=Profile+views)

</div>

---

## 🚀 Featured Projects

### ✅ WordPress on AWS with Terraform
> Infrastructure as Code to deploy a fully automated WordPress environment on AWS.

[![Repo](https://img.shields.io/badge/GitHub-WordPress--en--AWS--con--Terraform-181717?style=flat-square&logo=github)](https://github.com/JesusCMM13/WordPress-en-AWS-con-Terraform)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=FF9900)
![Shell](https://img.shields.io/badge/Shell-121011?style=flat-square&logo=gnu-bash&logoColor=white)

Provisions a complete, production-ready WordPress stack from scratch using Terraform — no manual steps required. Includes a custom VPC with public subnet, Internet Gateway, Elastic IP, and an EC2 instance (`t3.small`, Amazon Linux 2023) with a 20GB encrypted gp3 volume. The `userdata.sh` script automatically installs and configures Apache, PHP-FPM, MariaDB and the latest WordPress release, with optional SSL via Let's Encrypt + Certbot.

**Key highlights:** modular `variables.tf` for full customization · sensitive values kept out of the repo via `.gitignore` · cost breakdown included in the docs · optional HTTPS with any domain pointing to the Elastic IP.

---

### 🚧 Microservices Infrastructure on AWS EKS *(TFG — In Progress)*
> End-to-end cloud-native infrastructure: from local Docker Compose to a production EKS cluster, with full CI/CD pipeline.

[![Repo](https://img.shields.io/badge/GitHub-TFG__Infraestructura__microservicios__AWS--EKS-181717?style=flat-square&logo=github)](https://github.com/JesusCMM13/TFG_Infraestructura_microservicios_AWS-EKS)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=FF9900)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

Final degree project (2º ASIR). Monorepo with a Vue 3 frontend and a NestJS/TypeScript backend, containerized with multi-stage Dockerfiles and orchestrated locally via Docker Compose. The CI/CD pipeline (GitHub Actions) runs linting, unit tests, Trivy vulnerability scanning and pushes images to Docker Hub on every push to `main`. The production environment is an Amazon EKS cluster (v1.30, 3× `t3.small` nodes) provisioned with Terraform, managed via Kubernetes manifests (Deployments, Services, Ingress, HPA, ConfigMaps & Secrets) and Portainer CE for visual cluster management.

**Key highlights:** DevSecOps-first approach with Trivy blocking CRITICAL/HIGH CVEs · Horizontal Pod Autoscaler (min 2 / max 6 replicas) · EBS-backed PostgreSQL persistence · full IaC from VPC to application layer.

---


> More projects coming soon! I'll be uploading work related to infrastructure deployment, container orchestration, and cloud automation. Stay tuned ⚙️

---

<div align="center">

*Thanks for stopping by! Feel free to connect on LinkedIn or explore the repos below* 🙌

</div>
