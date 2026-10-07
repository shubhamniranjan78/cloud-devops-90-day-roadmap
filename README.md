# 🚀 Cloud & DevOps 90-Day Roadmap

> **From Infrastructure Operations to Cloud & DevOps Engineering — Learn. Build. Automate. Deploy.**

This repository documents my **90-day hands-on journey toward Cloud & DevOps Engineering**.

I already have experience working with **Windows/Linux infrastructure, networking, virtualization, monitoring, incident management, and troubleshooting**. This roadmap builds on that foundation and adds the skills required to work with modern cloud and DevOps environments.

The goal is not simply to complete courses or collect certifications.

The goal is to **build real infrastructure, automate repetitive tasks, troubleshoot failures, document solutions, and develop production-oriented engineering habits.**

---

## 🎯 Objective

By the end of these 90 days, I aim to be comfortable with:

- ☁️ Microsoft Azure infrastructure
- 🐧 Linux administration
- ⚡ PowerShell automation
- 🏗️ Terraform / Infrastructure as Code
- 🔀 Git & GitHub
- 🔄 CI/CD pipelines
- 🐳 Docker
- 🐍 Python automation
- 📊 Monitoring & observability
- 🤖 Infrastructure automation
- 🔧 Cloud troubleshooting
- 🚀 End-to-end infrastructure projects

The ultimate goal is to transition from **Infrastructure Operations** toward:

```text
Cloud Operations Engineer
        ↓
Cloud Infrastructure Engineer
        ↓
DevOps Engineer
        ↓
Platform / SRE Engineer
```

---

# 🗺️ Roadmap

```text
                    ┌────────────────────┐
                    │ Infrastructure     │
                    │ Operations         │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Linux + PowerShell │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Azure              │
                    │ Cloud              │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Terraform          │
                    │ Infrastructure IaC │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Git + CI/CD        │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Docker             │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Python + Automation│
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Monitoring +       │
                    │ Observability      │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Cloud / DevOps     │
                    │ Projects           │
                    └────────────────────┘
```

---

# 📅 90-Day Plan

## Phase 1 — Foundation

**Days 1–20**

Focus:

- Linux fundamentals
- Linux administration
- Networking fundamentals
- PowerShell
- Windows administration
- Azure fundamentals
- Azure CLI

### Outcome

Build a strong foundation for managing cloud infrastructure from both Windows and Linux environments.

---

## Phase 2 — Azure Infrastructure

**Days 21–35**

Focus:

- Azure Resource Groups
- Virtual Machines
- VNets
- Subnets
- NSGs
- Storage
- Azure Monitor
- Log Analytics
- RBAC
- Azure CLI
- Azure PowerShell

### Outcome

Deploy and manage a practical Azure infrastructure environment.

---

## Phase 3 — Infrastructure as Code

**Days 36–50**

Focus:

- Terraform fundamentals
- Providers
- Resources
- Variables
- Outputs
- State
- Modules
- Terraform with Azure
- Infrastructure lifecycle

### Outcome

Move from manually creating infrastructure to **repeatable Infrastructure as Code**.

---

## Phase 4 — Git & CI/CD

**Days 51–60**

Focus:

- Git fundamentals
- Branching
- Pull requests
- GitHub
- GitHub Actions
- CI/CD concepts
- Terraform validation
- Automated deployment

### Outcome

Create a workflow where infrastructure changes can be version-controlled and automatically validated.

---

## Phase 5 — Containers

**Days 61–68**

Focus:

- Docker fundamentals
- Images
- Containers
- Dockerfiles
- Volumes
- Networks
- Docker Compose
- Container troubleshooting

### Outcome

Understand how applications are packaged and deployed using containers.

---

## Phase 6 — Python & Automation

**Days 69–77**

Focus:

- Python fundamentals
- Functions
- Files
- JSON
- APIs
- Requests
- Infrastructure automation
- Cloud automation

### Outcome

Build scripts that interact with infrastructure and APIs.

---

## Phase 7 — Monitoring & Observability

**Days 78–84**

Focus:

- Metrics
- Logs
- Alerts
- Azure Monitor
- Log Analytics
- Infrastructure health checks
- Incident investigation
- Automated remediation

### Outcome

Build monitoring workflows similar to real infrastructure operations environments.

---

## Phase 8 — Capstone Project & Career Preparation

**Days 85–90**

Build and document the flagship project.

Focus:

- Project completion
- Architecture documentation
- GitHub cleanup
- Resume updates
- Interview preparation
- Cloud/DevOps interview questions
- Job applications

---

# 🛠️ Flagship Project

## Azure Infrastructure Monitoring & Auto-Remediation Platform

The main project brings the skills from this roadmap together.

```text
                GitHub
                   │
                   ▼
            GitHub Actions
                   │
                   ▼
              Terraform
                   │
                   ▼
          Azure Infrastructure
                   │
          ┌────────┴────────┐
          ▼                 ▼
      Windows VM         Linux VM
          │                 │
          └────────┬────────┘
                   ▼
             Azure Monitor
                   │
                   ▼
             Alerts / Logs
                   │
                   ▼
          Automation Scripts
          PowerShell / Python
                   │
                   ▼
             Remediation
                   │
                   ▼
              Verification
```

### The platform will monitor scenarios such as:

- High CPU utilization
- High memory utilization
- Low disk space
- Windows service failures
- Linux service failures
- System/application events
- VM availability
- Infrastructure health

### Example workflow

```text
Problem Detected
       ↓
Alert Generated
       ↓
Investigate
       ↓
Automation Triggered
       ↓
Remediation
       ↓
Health Check
       ↓
Incident Documentation
```

---

# 📂 Repository Structure

```text
cloud-devops-90-day-roadmap/
│
├── README.md
├── ROADMAP.md
│
├── roadmaps/
│   ├── azure.md
│   ├── linux.md
│   ├── powershell.md
│   ├── terraform.md
│   ├── git-github.md
│   ├── cicd.md
│   ├── docker.md
│   ├── python.md
│   └── monitoring.md
│
├── plans/
│   ├── 90-day-plan.csv
│   └── weekly-checklist.md
│
├── projects/
│   └── azure-monitoring-auto-remediation/
│       ├── terraform/
│       ├── powershell/
│       ├── python/
│       ├── monitoring/
│       └── README.md
│
├── interview-prep/
│   ├── azure.md
│   ├── linux.md
│   ├── networking.md
│   ├── terraform.md
│   ├── docker.md
│   └── devops.md
│
└── .github/
    └── workflows/
        └── terraform.yml
```

---

# 📊 Skills Progress

| Skill | Status | Target |
|---|---|---|
| Azure | 🟡 Learning | 🟢 Hands-on |
| Linux | 🟡 Learning | 🟢 Working proficiency |
| PowerShell | 🟡 Learning | 🟢 Automation |
| Terraform | 🟡 Learning | 🟢 IaC projects |
| Git/GitHub | 🟡 Learning | 🟢 Daily usage |
| CI/CD | 🔴 Starting | 🟢 Working pipeline |
| Docker | 🔴 Starting | 🟢 Working proficiency |
| Python | 🔴 Starting | 🟢 Automation |
| Monitoring | 🟢 Experienced | 🟢 Cloud observability |
| Networking | 🟢 Experienced | 🟢 Cloud networking |

> **Legend:** 🔴 Not started · 🟡 Learning · 🟢 Working proficiency

---

# 📈 Daily Learning Method

Each study day follows the same engineering workflow:

```text
Learn
  ↓
Practice
  ↓
Build
  ↓
Break
  ↓
Troubleshoot
  ↓
Document
  ↓
Commit to Git
```

Every day should produce something tangible whenever possible:

- A script
- A Terraform configuration
- A Git commit
- A troubleshooting note
- A lab
- A diagram
- A documented incident
- A working automation
- An interview answer

---

# ⏱️ Recommended Daily Routine

### Weekdays

**2–3 hours/day**

```text
30 min → Theory
60 min → Hands-on lab
30 min → Project
20 min → Documentation
10 min → Git commit
```

### Weekends

**3–4 hours/day**

Use the additional time for:

- Project development
- Revision
- Troubleshooting
- Interview preparation
- Resume/portfolio improvements

---

# 🧠 Engineering Principles

This roadmap follows a few simple principles:

### 1. Don't just watch tutorials

If I learn Terraform, I should write Terraform.

If I learn PowerShell, I should automate something.

If I learn Azure, I should deploy something.

---

### 2. Break things intentionally

Infrastructure engineers learn by troubleshooting.

Create failures, investigate them, fix them, and document the solution.

---

### 3. Automate repetitive work

If a task can be repeated reliably by a script or pipeline, automate it.

---

### 4. Document everything important

A solution isn't complete until another engineer can understand and reproduce it.

---

### 5. Commit regularly

Git history should show the progression of the project and the learning journey.

---

# 🎯 Success Criteria

At the end of 90 days, the target is to have:

- [ ] Completed the 90-day roadmap
- [ ] Built Azure infrastructure using Terraform
- [ ] Created PowerShell automation
- [ ] Written Python automation scripts
- [ ] Created a GitHub Actions pipeline
- [ ] Containerized an application with Docker
- [ ] Implemented Azure monitoring
- [ ] Built automated remediation
- [ ] Documented architecture and troubleshooting
- [ ] Created a portfolio-ready capstone project
- [ ] Updated resume with project evidence
- [ ] Prepared Cloud/DevOps interview questions
- [ ] Started applying for Cloud Operations / Cloud Infrastructure roles

---

# 💼 Target Roles

This roadmap is designed to support applications for:

- Cloud Operations Engineer
- Azure Cloud Support Engineer
- Cloud Infrastructure Engineer
- Infrastructure Engineer
- Systems Engineer
- DevOps Engineer — Junior
- Cloud Automation Engineer
- Infrastructure Automation Engineer
- Platform Engineer — Junior
- Site Reliability Engineer — Junior

---

# 📌 Progress Tracking

I will track progress using:

```text
Day → Task → Output → Git Commit → Review
```

The objective is not to achieve **90/90 perfect days**.

The objective is to keep moving forward and build **visible evidence of technical growth**.

---

# 🚀 Final Goal

The destination isn't simply a certification.

It is the ability to take an infrastructure problem and work through the complete engineering lifecycle:

> **Detect → Investigate → Automate → Deploy → Monitor → Remediate → Document**

That is the skill set I am building over these 90 days.

---

## 👨‍💻 About Me

I'm an **IT Infrastructure / Operations Engineer** with experience across Windows/Linux servers, networking, virtualization, monitoring, incident management and infrastructure troubleshooting.

This repository represents my transition toward **Cloud, Infrastructure Automation and DevOps Engineering**.

**Learning in public. Building in public. Improving every day.**

---

⭐ If this roadmap or any of the projects helps you, feel free to explore the repository and follow the journey.
