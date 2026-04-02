# Hi, I'm Thiruvarul G 👋

**AWS DevOps Engineer** — I build production-grade cloud systems that are secure, automated, and designed to survive real-world failures.

- 🏗️ 5 end-to-end cloud projects — from infrastructure provisioning to incident response
- ☁️ AWS-focused: EKS, CloudFormation, SSM, Secrets Manager, CloudWatch
- 🔒 Security-first: zero open ports, SSM-only access, KMS-encrypted secrets, least-privilege IAM
- 📊 Observability built-in: Prometheus + Grafana + CloudWatch across every project
- 📍 Tamil Nadu, India &nbsp;|&nbsp; Open to remote opportunities

---

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Thiru-2004-varul&show_icons=true&theme=default&hide_border=true&count_private=true)
&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Thiru-2004-varul&layout=compact&hide_border=true&theme=default)

---

## ⚡ What I build

| Area | What I deliver |
|---|---|
| **High availability** | Multi-AZ AWS infrastructure with 95%+ uptime, ALB failover, Auto Scaling |
| **Zero-trust access** | No public IPs, no SSH — SSM Session Manager only, sessions logged to S3 + CloudTrail |
| **Infrastructure as code** | Terraform modules + CloudFormation stacks — full environment in minutes, not days |
| **Configuration management** | Ansible playbooks over SSM — OS hardening, agent deployment, app config at scale |
| **CI/CD pipelines** | GitHub Actions — test → Trivy scan → ECR push → EKS deploy, OIDC auth, no stored keys |
| **Observability** | Prometheus + Grafana + CloudWatch — 70% faster issue detection, custom /metrics endpoint |
| **Incident response** | Simulated EC2 failure, CPU spike, secret failure — measured detection time and RTO |

---

## 🛠️ Tech stack

**Cloud — AWS**
`EC2` `VPC` `IAM` `ALB` `S3` `EKS` `Lambda` `CloudWatch` `CloudFormation`
`Systems Manager (SSM)` `Secrets Manager` `KMS` `CloudTrail` `SNS` `Auto Scaling` `NAT Gateway`

**Infrastructure as code**
`Terraform` `CloudFormation` — modules, remote state, stack dependency management

**Configuration management**
`Ansible` — dynamic aws_ec2 inventory, playbooks over SSM, idempotent OS hardening

**Containers & orchestration**
`Docker` `Kubernetes (EKS)` — Rolling Update, RBAC, ClusterRole, RoleBinding, ConfigMaps

**CI/CD & security scanning**
`GitHub Actions` — Trivy container scan, ECR push, Kubernetes dry-run, OIDC/IRSA (no stored credentials)

**Monitoring & observability**
`Prometheus` `Grafana` `AWS CloudWatch` — alarms, Log Insights, custom Flask /metrics endpoint

**Scripting & programming**
`Python (Flask, OOP)` `Bash` — automation scripts, cron jobs, health-check tooling

**Security**
`IAM least-privilege` `RBAC` `OIDC` `KMS encryption` `Private subnets` `UFW firewall` `SSM Patch Manager`

**OS & tools**
`Linux (Ubuntu 22.04)` `Git` `GitHub` `Minikube` `VS Code`

---

## 🚀 Featured projects

---

### 🏆 AWS Cloud Operations Platform
> Full operations lifecycle — provisioning, security, config management, monitoring, DR, incident response

- Deployed **7 dependent CloudFormation stacks** in strict dependency order (network → security → compute → SSM / Secrets / Backup / Monitoring)
- **Zero SSH** — all EC2 access via SSM Session Manager, every session auto-logged to S3 + CloudTrail
- **Ansible over SSM** — dynamic aws_ec2 inventory, OS hardening, CloudWatch Agent, Flask app deploy — no open ports needed
- **Incident simulation** — EC2 failure, high CPU, Secrets Manager outage — detection time and RTO measured and documented

`CloudFormation` `SSM` `Secrets Manager` `Ansible` `CloudWatch` `KMS` `SNS` `IAM` `EC2` `ALB`

👉 [github.com/Thiru-2004-varul/aws-cloud-operations-platform](https://github.com/Thiru-2004-varul/aws-cloud-operations-platform)

---

### Enterprise Internal Developer Platform (IDP)
> Self-service environment provisioning for teams — no tickets, no waiting

- Teams provision their own AWS environments by editing **one Terraform config file**
- Separate **ClusterRoles + RoleBindings** per environment (dev / staging / prod) — least-privilege RBAC enforced
- Composable Terraform modules for networking, compute, security, EKS — **new environment in minutes**
- Secure by default: private subnets, least-privilege IAM, nothing public unless explicitly declared

`Terraform (Modular)` `EKS` `Kubernetes RBAC` `VPC` `IAM` `EC2`

👉 [github.com/Thiru-2004-varul/enterprise-idp-platform](https://github.com/Thiru-2004-varul/enterprise-idp-platform)

---

### Zero-Downtime Kubernetes Deployment on EKS
> Proved 0 seconds downtime during a live v1 → v2 migration — Prometheus flat line is the proof

- **5-stage GitHub Actions pipeline**: test → Trivy scan → ECR push → Terraform plan → EKS deploy
- Rolling Update with `maxUnavailable: 0` — new pod healthy before old pod terminates
- **OIDC/IRSA auth** — no AWS keys stored anywhere in the pipeline
- Every curl response during migration logged — zero errors, zero gaps

`Python Flask` `Docker` `Kubernetes` `EKS` `Terraform` `GitHub Actions` `Prometheus` `Grafana` `ECR` `OIDC`

👉 [github.com/Thiru-2004-varul/virtual-server-co-migration](https://github.com/Thiru-2004-varul/virtual-server-co-migration)

---

### Secure Multi-AZ Private Web Infrastructure
> 95%+ uptime — built to survive an entire Availability Zone going down

- EC2 across 2 AZs, ALB reroutes traffic within seconds of a zone failure
- **Zero public server exposure** — private subnets, Bastion Host as only entry point
- Full environment created or destroyed with **one Terraform command in under 5 minutes**

`Terraform` `AWS VPC` `EC2` `ALB` `IAM` `NAT Gateway` `Security Groups` `Bastion Host`

👉 [github.com/Thiru-2004-varul/secure-multi-az-private-web-infra](https://github.com/Thiru-2004-varul/secure-multi-az-private-web-infra)

---

### CloudWatch Observability Platform
> 70% faster problem detection — replaced manual log reading with automated alerting

- CloudWatch Alarms + Grafana dashboard — alerts before users notice issues
- Custom Flask `/metrics` endpoint feeds live request count and uptime into Prometheus
- CloudWatch Log Insights queries replace minutes of manual log searching with seconds

`CloudWatch` `Prometheus` `Grafana` `EC2` `Python Flask` `Log Insights` `SNS`

👉 [github.com/Thiru-2004-varul/cloudwatch-observability-platform](https://github.com/Thiru-2004-varul/cloudwatch-observability-platform)

---

## 📈 Currently learning

- **Helm** — Kubernetes package management for production workloads
- **AWS Solutions Architect Associate (SAA-C03)** — after AWS CCP
- **Platform Engineering** — developer experience, internal tooling, GitOps patterns
- **Cloud Security** — GuardDuty, Security Hub, IAM Access Analyzer

---

## 📫 Let's connect

| | |
|---|---|
| 📧 Email | thiruvarulg9@gmail.com |
| 💼 LinkedIn | [linkedin.com/in/thiruvarul-g-051690260](https://www.linkedin.com/in/thiruvarul-g-051690260) |
| 📍 Location | Tamil Nadu, India — open to remote |

---

*Building secure, automated, and reliable cloud infrastructure — one stack at a time.*

![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900?logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-EKS-326CE5?logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-Automation-EE0000?logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?logo=githubactions&logoColor=white)
![Python](https://img.shields.io/badge/Python-Flask-3776AB?logo=python&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-E6522C?logo=prometheus&logoColor=white)
