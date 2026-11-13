# Hi, I'm Olamide Osundahunsi (Jedi) 👋

**DevOps, Cloud & Linux Systems Engineer** | **B.Tech. Computer Science (Final Year)** | **Lagos, Nigeria (Open to Remote)**

I design and automate secure, reproducible, and cost-efficient cloud infrastructure on **AWS**, **GCP**, and **Ubuntu 24.04 LTS**. My focus is on zero-trust CI/CD pipelines, Infrastructure as Code, containerization, and observability.

---

### What I Build & Operate

* **Keyless CI/CD & Zero-SSH Deployments:** GitHub Actions with **OIDC federation** (`AssumeRoleWithWebIdentity`) + **AWS Systems Manager (SSM)** Run Command—eliminating static cloud credentials and closing inbound port 22.
* **Infrastructure as Code & Configuration Management:** **Terraform** (custom VPCs, multi-AZ subnets, chained Security Groups, RDS, IAM, S3 remote state with native `use_lockfile` locking) and **Ansible** (idempotent Ubuntu provisioning, Jinja2 templates, `systemd` services & timers).
* **Containers & Artifact Pipelines:** **Docker**, **Docker Compose**, GitHub Container Registry (**GHCR**), and immutable S3 *"Build Once, Ship Artifact"* delivery pipelines.
* **Observability & Database Security:** **AWS CloudWatch Unified Agent** (guest-OS memory telemetry & Linux OOM prevention), **Prometheus**, **Loki**, **Grafana**, and declarative **PostgreSQL 15+** least-privilege RBAC.

---

### Core Tech Stack

* **Cloud:** AWS (`EC2`, `VPC`, `RDS`, `S3`, `IAM`, `SSM`, `CloudWatch`, `SNS`, `SES`, `Elastic Beanstalk`, `ElastiCache`, `Amazon MQ`), GCP (`VPC`, `MIG`, `Cloud SQL`, `Cloud NAT`, `HTTPS LB`)
* **IaC & Automation:** Terraform, Ansible, Bash, GitHub Actions, Jenkins
* **OS & Containers:** Ubuntu 24.04 LTS (Desktop & Server), Docker, Docker Compose, `systemd`, `rsyslog`, `journald`, Nginx
* **Languages & Data:** Python (`FastAPI`, `Django`, `Celery`, `pytest`, `ruff`), PostgreSQL, SQL, C#, TypeScript (`NestJS`, `Prisma`)

---

### Featured Infrastructure Work

* [**ps-price-tracker**](https://github.com/JediFromOhio/ps-price-tracker) — End-to-end AWS price-tracking infrastructure provisioned with **Terraform** (two-stage S3 remote state + `use_lockfile`), **Ansible**, **Docker/GHCR**, **systemd timers**, and **GitHub Actions OIDC + SSM**.
* **Percerpt (DevOps Lead)** — Multi-service financial platform (`NestJS` + `FastAPI` + `RDS PostgreSQL`) featuring keyless OIDC/SSM CI/CD, S3 artifact deployments with sub-60s rollbacks, ARN-scoped IAM isolation, CloudWatch RAM/OOM alerting, and declarative PostgreSQL RBAC.
* [**vprofile-project**](https://github.com/JediFromOhio/vprofile-project) — Multi-cloud refactoring across AWS PaaS (`Beanstalk`, `RDS`, `ElastiCache`, `Amazon MQ`) and GCP (`VPC`, `MIG`, `Cloud SQL`), paired with `Prometheus`, `Loki`, `Grafana`, and `Jenkins`.

---

### Connect

* **Email:** osundahunsiolamide@gmail.com
* **Portfolio / Domain:** [jedibuilds.tech](https://jedibuilds.tech)
