# 2-Month Cloud Engineering Hands-On Plan

> Approx. 2 hours/day weekdays + 4-6 hours/weekends  
> Focus on practice through labs and projects

---

## Month 1 — Linux, Networking, Python & API Development

### Week 1 — Linux CLI & Shell Scripting Basics

| Day  | Task                                                | Est. Time | Resources                                   |
|-------|----------------------------------------------------|-----------|---------------------------------------------|
| Mon   | Learn `ls`, `cd`, `cat`, `head`, `tail` commands  | 2 hrs     | [Linux Command Tutorial](https://linuxjourney.com/lesson/ls-command) |
| Tue   | Practice `grep`, `find`, `sort`, `uniq`            | 2 hrs     | [Grep Guide](https://www.freecodecamp.org/news/grep-command-explained-with-examples/) |
| Wed   | Text processing with `awk`, `sed` basics           | 2 hrs     | [Awk Tutorial](https://www.grymoire.com/Unix/Awk.html) |
| Thu   | Vim basics and editing practice                      | 2 hrs     | [Vim Tutor](https://www.openvim.com/)      |
| Fri   | Write shell script for automated backups and cleanup | 2 hrs    | [Shell Scripting Guide](https://www.shellscript.sh/) |
| Sat   | Setup Ubuntu VM (VirtualBox/WSL), run scripts       | 4-6 hrs   | [Ubuntu VM Setup](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview) |
| Sun   | Document scripts, push to GitHub                     | 4 hrs     | [GitHub Docs](https://docs.github.com/en/get-started/quickstart) |

---

### Week 2 — Networking & System Admin Basics

| Day  | Task                                                | Est. Time | Resources                                   |
|-------|----------------------------------------------------|-----------|---------------------------------------------|
| Mon   | Networking basics: `ip addr`, `ip link`, `ip route`| 2 hrs     | [IP Command Tutorial](https://linuxize.com/post/linux-ip-command/) |
| Tue   | Network connections: `netstat`, `ss`                | 2 hrs     | [Netstat Guide](https://www.geeksforgeeks.org/netstat-command-in-linux-with-examples/) |
| Wed   | Capture packets with `tcpdump`                       | 2 hrs     | [Tcpdump Tutorial](https://danielmiessler.com/study/tcpdump/) |
| Thu   | Configure firewall with `firewall-cmd` or `ufw`     | 2 hrs     | [FirewallD Docs](https://firewalld.org/documentation/) |
| Fri   | Systemd service files & logging with `journalctl`   | 2 hrs     | [Systemd Guide](https://www.freedesktop.org/software/systemd/man/systemd.service.html) |
| Sat   | Create monitoring bash script + systemd service     | 4-6 hrs   | [Systemd Service Example](https://www.freedesktop.org/software/systemd/man/systemd.service.html) |
| Sun   | Test & debug script, add logging                     | 4 hrs     | —                                           |

---

### Week 3 — Python Basics

| Day  | Task                                                | Est. Time | Resources                                   |
|-------|----------------------------------------------------|-----------|---------------------------------------------|
| Mon   | Python intro: variables, types, input/output       | 2 hrs     | [Python Official Tutorial](https://docs.python.org/3/tutorial/index.html) |
| Tue   | Control flow: loops, if/else, comprehensions       | 2 hrs     | [Python Control Flow](https://realpython.com/python-conditional-statements/) |
| Wed   | Functions, exception handling, file I/O             | 2 hrs     | [Python Functions](https://realpython.com/defining-your-own-python-function/) |
| Thu   | Object-oriented programming basics                  | 2 hrs     | [OOP in Python](https://realpython.com/python3-object-oriented-programming/) |
| Fri   | Setup VS Code environment + pipenv                   | 2 hrs     | [VS Code Python](https://code.visualstudio.com/docs/python/python-tutorial) |
| Sat   | Build log parser script: read logs, analyze failed logins | 4-6 hrs | *(Create own project)*                        |
| Sun   | Push code to GitHub, write README                    | 4 hrs     | —                                           |

---

### Week 4 — API Development with FastAPI

| Day  | Task                                                | Est. Time | Resources                                   |
|-------|----------------------------------------------------|-----------|---------------------------------------------|
| Mon   | Install FastAPI & Uvicorn, build “Hello World” API | 2 hrs     | [FastAPI Tutorial](https://fastapi.tiangolo.com/tutorial/) |
| Tue   | Build CRUD endpoints: Create, Read, Update, Delete | 2 hrs     | [FastAPI CRUD](https://fastapi.tiangolo.com/tutorial/sql-databases/) |
| Wed   | Use Pydantic models for validation                   | 2 hrs     | [Pydantic Docs](https://pydantic-docs.helpmanual.io/) |
| Thu   | Error handling and response status codes             | 2 hrs     | [Error Handling](https://fastapi.tiangolo.com/tutorial/handling-errors/) |
| Fri   | Write unit tests with pytest                          | 2 hrs     | [Testing FastAPI](https://fastapi.tiangolo.com/tutorial/testing/) |
| Sat   | Add SQLite support, test API locally with Postman    | 4-6 hrs   | —                                           |
| Sun   | Finalize project, Git push, README, API docs         | 4 hrs     | —                                           |

---

## Month 2 — Containerization, Azure, DevOps & Security

### Week 5 — Docker & Azure Deployment

| Day  | Task                                                | Est. Time | Resources                                   |
|-------|----------------------------------------------------|-----------|---------------------------------------------|
| Mon   | Write Dockerfile for FastAPI app                     | 2 hrs     | [Docker FastAPI](https://testdriven.io/blog/fastapi-docker/) |
| Tue   | Build & run Docker container locally                 | 2 hrs     | [Docker Tutorial](https://docs.docker.com/get-started/) |
| Wed   | Setup PostgreSQL container & connect API             | 2 hrs     | [Docker Compose example](https://docs.docker.com/compose/) |
| Thu   | Push Docker image to Docker Hub or Azure Container Registry | 2 hrs | [Push to Docker Hub](https://docs.docker.com/docker-hub/repos/) |
| Fri   | Deploy container to Azure App Service via CLI        | 2 hrs     | [Deploy to Azure](https://learn.microsoft.com/en-us/azure/app-service/tutorial-custom-container?pivots=container-linux) |
| Sat   | Deploy full stack to Azure, test and debug           | 4-6 hrs   | —                                           |
| Sun   | Document deployment process in GitHub                 | 4 hrs     | —                                           |

---

### Week 6 — CI/CD and Infrastructure as Code (IaC)

| Day  | Task                                                | Est. Time | Resources                                   |
|-------|----------------------------------------------------|-----------|---------------------------------------------|
| Mon   | GitHub Actions: build and test Docker image         | 2 hrs     | [GitHub Actions Docker](https://docs.github.com/en/actions/publishing-packages/publishing-docker-images) |
| Tue   | Extend workflow: push image to Azure Container Registry (ACR) | 2 hrs | —                                           |
| Wed   | Write Terraform scripts for Azure resources          | 2 hrs     | [Terraform Azure](https://learn.hashicorp.com/collections/terraform/azure-get-started) |
| Thu   | Add Terraform apply to GitHub Actions workflow       | 2 hrs     | —                                           |
| Fri   | Store DB passwords in Azure Key Vault and use in app | 2 hrs     | [Azure Key Vault Tutorial](https://learn.microsoft.com/en-us/azure/key-vault/secrets/quick-create-portal) |
| Sat   | Build full CI/CD pipeline + Infra as Code             | 4-6 hrs   | —                                           |
| Sun   | Push pipeline & scripts, write documentation          | 4 hrs     | —                                           |

---

### Week 7 — Cloud Security Fundamentals

| Day  | Task                                                | Est. Time | Resources                                   |
|-------|----------------------------------------------------|-----------|---------------------------------------------|
| Mon   | Assign Azure RBAC roles for least privilege          | 2 hrs     | [Azure RBAC Docs](https://learn.microsoft.com/en-us/azure/role-based-access-control/overview) |
| Tue   | Enable HTTPS with Azure App Service TLS certificates | 2 hrs     | [TLS in Azure](https://learn.microsoft.com/en-us/azure/app-service/configure-ssl-bindings) |
| Wed   | Scan Docker image with Trivy, code with Bandit        | 2 hrs     | [Trivy](https://aquasecurity.github.io/trivy/), [Bandit](https://bandit.readthedocs.io/en/latest/) |
| Thu   | Integrate security scans into CI pipeline             | 2 hrs     | —                                           |
| Fri   | Review Azure Security Center recommendations           | 2 hrs     | —                                           |
| Sat   | Harden app security: RBAC, TLS, scanning              | 4-6 hrs   | —                                           |
| Sun   | Document security setup & checklist                    | 4 hrs     | —                                           |

---

### Week 8 — Advanced Security & Monitoring

| Day  | Task                                                | Est. Time | Resources                                   |
|-------|----------------------------------------------------|-----------|---------------------------------------------|
| Mon   | Configure Network Security Groups (NSGs)             | 2 hrs     | [Azure NSG](https://learn.microsoft.com/en-us/azure/virtual-network/network-security-groups-overview) |
| Tue   | Setup Azure Monitor & Application Insights           | 2 hrs     | [Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-monitor/overview) |
| Wed   | Enable Multi-Factor Authentication (MFA)             | 2 hrs     | [Azure MFA](https://learn.microsoft.com/en-us/azure/active-directory/authentication/concept-mfa-howitworks) |
| Thu   | Perform threat modeling on app architecture           | 2 hrs     | [Threat Modeling Guide](https://owasp.org/www-project-threat-modeling/) |
| Fri   | Patch, rotate secrets, finalize security audit        | 2 hrs     | —                                           |
| Sat   | Final project: secure, monitored, audited cloud app   | 4-6 hrs   | —                                           |
| Sun   | Finalize documentation, push to GitHub                 | 4 hrs     | —                                           |
---

## Projects

### 1. Linux Sysadmin Automation Script  
**Goal:** Create bash scripts to automate system maintenance tasks such as backups, log rotation, and user management.  
**Skills:** Bash scripting, cron jobs, systemd services, logging.

### 2. Python Log Parser  
**Goal:** Build a Python script that parses system or application logs, identifies failed login attempts or errors, and generates reports.  
**Skills:** Python file I/O, regex, exception handling, CLI tools.

### 3. REST API with FastAPI  
**Goal:** Develop a RESTful API with CRUD operations backed by SQLite/PostgreSQL. Include input validation, error handling, and unit tests.  
**Skills:** FastAPI, Pydantic, testing with pytest, database integration.

### 4. Dockerized API Deployment  
**Goal:** Containerize your API using Docker and deploy it to Azure App Service or Azure Container Instances.  
**Skills:** Docker, Azure CLI, container registries, deployment.

### 5. CI/CD Pipeline  
**Goal:** Build an automated pipeline using GitHub Actions to build, test, and deploy your Dockerized app to Azure.  
**Skills:** GitHub Actions workflows, secrets management, Infrastructure as Code with Terraform.

### 6. Cloud Security Hardening  
**Goal:** Implement cloud security best practices including role-based access control, TLS, scanning with Trivy/Bandit, and monitoring with Azure Security Center.  
**Skills:** Azure IAM, security scanning, logging, threat modeling.

---

# Additional Resources

- [FastAPI Official Repo](https://github.com/tiangolo/fastapi)  
- [Terraform Azure Examples](https://github.com/Azure/terraform-azurerm-compute)  
- [GitHub Actions Marketplace](https://github.com/marketplace?type=actions)  
- Security tools:  
  - `trivy image your-image-name`  
  - `bandit -r your_project_folder`

---

# Notes

- Adjust pacing to fit your schedule.  
- Use the GitHub repo to track progress and save your scripts/projects.  
- Use VS Code extensions for better Python and Terraform experience.  
- Focus on learning by doing—experiment and break things safely!

---

**Ready to start?**  
Happy cloud engineering! ☁️🚀

