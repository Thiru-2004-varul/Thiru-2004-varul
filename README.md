<div align="center">

# Thiruvarul G 👋

### AWS DevOps Engineer

*Secure infrastructure · Zero-downtime deployments · Full observability*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thiruvarul-g-051690260)
[![Email](https://img.shields.io/badge/Email-thiruvarulg9@gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:thiruvarulg9@gmail.com)
[![Location](https://img.shields.io/badge/Tamil%20Nadu%2C%20India-Open%20to%20Remote-28a745)](https://www.linkedin.com/in/thiruvarul-g-051690260)

</div>

---

## About

I design and operate production-grade AWS infrastructure — multi-AZ, zero-trust, fully automated. Every system I build is observable from day one, hardened by default, and deployable with a single command.

**95%+ uptime** on multi-AZ setups &nbsp;·&nbsp; **70% faster** incident detection &nbsp;·&nbsp; **0 seconds** downtime on live Kubernetes migrations &nbsp;·&nbsp; **Zero SSH** across all environments

---

## Tech stack

| | |
|---|---|
| **Cloud** | AWS — EC2, VPC, IAM, ALB, S3, EKS, Lambda, CloudFormation, SSM, Secrets Manager, KMS, CloudTrail, SNS, Auto Scaling |
| **IaC** | Terraform (modules, remote state), CloudFormation (7-stack dependency chains) |
| **Config mgmt** | Ansible — dynamic `aws_ec2` inventory, playbooks over SSM, OS hardening |
| **Containers** | Docker, Kubernetes EKS — Rolling Update, RBAC, ClusterRole, RoleBinding |
| **CI/CD** | GitHub Actions — Trivy scan, ECR push, OIDC/IRSA auth (zero stored credentials) |
| **Observability** | Prometheus, Grafana, CloudWatch Alarms, Log Insights, custom `/metrics` endpoint |
| **Security** | Least-privilege IAM, RBAC, KMS encryption, private subnets, SSM Patch Manager, UFW |
| **Scripting** | Python (Flask), Bash — automation scripts, health checks, cron jobs |
| **OS & tools** | Linux (Ubuntu 22.04), Git, Minikube, VS Code |

---

## Projects

### 🏆 AWS Cloud Operations Platform
> `CloudFormation` `SSM` `Ansible` `Secrets Manager` `KMS` `CloudWatch` `SNS` `IAM`

Full operations lifecycle — provisioning, security, config management, monitoring, DR, and incident response in one platform. 7 CloudFormation stacks in strict dependency order. Zero SSH — SSM only, every session logged to S3 and CloudTrail. Incidents simulated, RTO documented.

🔗 [View project](https://github.com/Thiru-2004-varul/aws-cloud-operations-platform)

---

### Enterprise Internal Developer Platform (IDP)
> `Terraform (Modular)` `EKS` `Kubernetes RBAC` `VPC` `IAM`

Teams self-provision AWS environments by editing one config file — no tickets, no waiting. Separate ClusterRoles per environment (dev / staging / prod), composable Terraform modules, secure by default.

🔗 [View project](https://github.com/Thiru-2004-varul/enterprise-idp-platform)

---

### Zero-Downtime Kubernetes Deployment on EKS
> `Docker` `EKS` `Terraform` `GitHub Actions` `Prometheus` `Grafana` `ECR` `OIDC`

Live v1 → v2 migration with zero service interruption — Prometheus flat line is the proof. 5-stage CI/CD pipeline, `maxUnavailable: 0` rolling update, OIDC auth — no AWS keys stored anywhere.

🔗 [View project](https://github.com/Thiru-2004-varul/zero-downtime-virtual-server-co-migration.git)

---

### Secure Multi-AZ Private Web Infrastructure
> `Terraform` `VPC` `EC2` `ALB` `IAM` `NAT Gateway` `Bastion Host`

95%+ uptime across 2 Availability Zones. Zero public EC2 exposure — private subnets, Bastion Host only. Full environment up or destroyed with one Terraform command in under 5 minutes.

🔗 [View project](https://github.com/Thiru-2004-varul/secure-multi-az-private-web-infra)

---

### CloudWatch Observability Platform
> `CloudWatch` `Prometheus` `Grafana` `Python Flask` `SNS`

70% faster problem detection — replaced manual log reading with automated CloudWatch alarms and Grafana dashboards. Custom Flask `/metrics` endpoint, Log Insights for root cause in seconds.

🔗 [View project](https://github.com/Thiru-2004-varul/cloudwatch-observability-platform)

---

## Currently learning

`Helm` &nbsp;·&nbsp; `AWS SAA-C03` &nbsp;·&nbsp; `GitOps / ArgoCD` 

---

<div align="center">

![AWS](https://img.shields.io/badge/AWS-FF9900?logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

</div>
