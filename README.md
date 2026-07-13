# AWS Cloud Infrastructure Automation with Terraform

Welcome to my personal cloud engineering laboratory repository! This workspace tracks my progression through advanced Infrastructure as Code (IaC) architectures on Amazon Web Services (AWS) using HashiCorp Terraform. 

This repository serves as both an active codebase for live lab environments and a technical knowledge base documenting industry-grade implementations, security patterns, and cloud orchestration strategies.

---

## 📂 Project Organization & Architecture

```text
.
├── lesson-03/            # Hands-on Labs: EC2 Compute Provisioning & State Management
│   ├── main.tf           # Resource blueprints (Compute instances, AMI mapping)
│   └── .gitignore        # Explicit exclusion matrices (Excludes state files & provider binaries)
└── jogi-writes/          # Technical Blog Assets & Deep-Dive Notes
    └── README.md         # Professional Terraform & AWS Comprehensive Cheat Sheets

#Work in progress
```

* **Core Deployments:** Iterative exercises focusing on highly available infrastructure patterns, networking design (VPCs, Subnets), security groups, load balancing, and computing primitives.
* **Continuous Documentation:** Comprehensive blog breakdowns and real-world deployment playbooks mapped to industry compliance parameters.

---

## 📘 Detailed Study Notes & Cheat Sheets

Looking for comprehensive breakdowns of AWS integrations, environment setups, CLI parameter mappings, or technical blog posts for this course? 

👉 **Access the comprehensive repository logs here: [jogi-writes/](./jogi-writes/)**

Inside the **jogi-writes** directory, you will find:
* Detailed installation blueprints tailored for Windows PowerShell environment initialization.
* IAM non-root execution guidelines utilizing the principle of least privilege (`AdministratorAccess` isolation strategies).
* Troubleshooting playbooks tracking region-specific lookup exceptions like the `InvalidAMIID.NotFound` error.
* Virtualization and network adapter mapping parameters (NAT vs. NAT Network isolation).

---

## 🛠️ Native Development Workspace

This lab repository is built utilizing the following development matrix:
* **Infrastructure Engine:** Terraform v1.x+
* **Cloud Platform:** Amazon Web Services (AWS)
* **Local Control Plane:** Windows PowerShell CLI Environment / Linux Dev Containers
* **Integrated Development Environment (IDE):** Visual Studio Code (VS Code)
* **Terraform files by:** [Dave Prowse](https://github.com/daveprowse/tac-course)
---

## 🔐 Git & State Security Management

To maintain rigorous security compliance, this repository leverages an explicit `.gitignore` architecture. Local cloud provider binary suites, compiled variables, runtime state configurations, and deployment strategies containing cryptographic identifiers are completely decoupled from remote tracking:
* `.terraform/` (Cached infrastructure provider engines)
* `*.tfstate` / `*.tfstate.backup` (Target operational state state-mapping files)
* `.terraform.lock.hcl` (Fixed dependency hash validation trees)

---

*Happy Building! 🚀*
