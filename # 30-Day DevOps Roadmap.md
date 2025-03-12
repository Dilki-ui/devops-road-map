# 30-Day DevOps Roadmap
Become a proficient DevOps beginner in 30 days with 6 hours/day (~180 hours total). Focus: Linux, scripting, Git, cloud, containers, CI/CD, monitoring.

---

## Week 1: Foundations (Days 1-7)
**Goal**: Master Linux, scripting, and version control—core DevOps skills.  
**Daily Commitment**: 6h (~2h theory, 3h practice, 1h review).

### Day 1: Linux Basics
- **Theory (2h)**: Learn Linux fundamentals (file system, commands, permissions) via YouTube (e.g., "Learn Linux TV") or [Linux Journey](https://linuxjourney.com/).
- **Practice (3h)**: Set up Ubuntu VM (VirtualBox/WSL2). Use `ls`, `cd`, `chmod`, `chown`, `grep`, `find`.
- **Review (1h)**: Write a cheat sheet of 20 commands.

### Day 2: Linux System Administration
- **Theory (2h)**: Study users/groups, processes, package management (`apt`, `yum`).
- **Practice (3h)**: Create users, manage permissions, install `nginx`, monitor with `top`/`ps`.
- **Review (1h)**: Document web server setup steps.

### Day 3: Bash Scripting Basics
- **Theory (2h)**: Learn Bash variables, loops, conditionals, functions.
- **Practice (3h)**: Write scripts: (1) backup directory, (2) check disk space, (3) automate task (e.g., system update).
- **Review (1h)**: Debug and refine scripts.

### Day 4: Git and Version Control
- **Theory (2h)**: Learn Git basics (commits, branches, merges) via [Git Simple Guide](https://rogerdudler.github.io/git-guide/) or freeCodeCamp.
- **Practice (3h)**: Set up Git locally, create repo, commit, branch, merge, push to GitHub.
- **Review (1h)**: Summarize Git workflow (clone, branch, PR).

### Day 5: Git Collaboration
- **Theory (2h)**: Study pull requests, conflict resolution, GitHub workflows.
- **Practice (3h)**: Fork a repo, make changes, submit PR, resolve a conflict.
- **Review (1h)**: Write PR process guide.

### Day 6: Networking Basics
- **Theory (2h)**: Learn IP addressing, DNS, ports, protocols (HTTP, SSH).
- **Practice (3h)**: Use `ping`, `netstat`, `curl`, set up SSH, configure `ufw` firewall.
- **Review (1h)**: Explain SSH in your own words.

### Day 7: Mini Project + Review
- **Project (4h)**: Automate web server setup with Bash, version with Git, push to GitHub.
- **Review (2h)**: Revisit weak areas, solidify Linux/Git skills.

---

## Week 2: Cloud and Infrastructure (Days 8-14)
**Goal**: Learn cloud platforms and Infrastructure-as-Code (IaC).  
**Daily Commitment**: 6h (~2h theory, 3h practice, 1h review).

### Day 8: Cloud Basics (AWS/GCP/Azure)
- **Theory (2h)**: Pick AWS. Learn EC2, S3, VPC via free tier docs or [TechWorld with Nana](https://www.youtube.com/c/TechWorldwithNana).
- **Practice (3h)**: Sign up for AWS Free Tier, launch EC2, SSH in.
- **Review (1h)**: Document EC2 setup.

### Day 9: Cloud Storage and Networking
- **Theory (2h)**: Study S3 and networking (subnets, security groups).
- **Practice (3h)**: Upload to S3, configure security group for HTTP/SSH.
- **Review (1h)**: Explain S3 vs. EC2 storage.

### Day 10: Infrastructure as Code (Terraform)
- **Theory (2h)**: Learn Terraform basics (providers, resources, state) via [HashiCorp Tutorials](https://learn.hashicorp.com/terraform).
- **Practice (3h)**: Install Terraform, launch EC2 with config.
- **Review (1h)**: Debug Terraform code.

### Day 11: Terraform Advanced
- **Theory (2h)**: Explore variables, modules, outputs.
- **Practice (3h)**: Build reusable EC2 + S3 module.
- **Review (1h)**: Plan automation steps.

### Day 12: CI/CD Basics
- **Theory (2h)**: Learn CI/CD pipelines (GitHub Actions recommended).
- **Practice (3h)**: Set up GitHub repo with Actions workflow to lint/test code.
- **Review (1h)**: Diagram a CI/CD pipeline.

### Day 13: CI/CD with Deployment
- **Theory (2h)**: Study cloud deployment via CI/CD.
- **Practice (3h)**: Deploy static site to S3 with GitHub Actions.
- **Review (1h)**: Troubleshoot pipeline.

### Day 14: Mini Project + Review
- **Project (4h)**: Use Terraform to deploy EC2 web server, automate with GitHub Actions.
- **Review (2h)**: Refine project, document process.

---

## Week 3: Containers and Orchestration (Days 15-21)
**Goal**: Master Docker and intro to Kubernetes.  
**Daily Commitment**: 6h (~2h theory, 3h practice, 1h review).

### Day 15: Docker Basics
- **Theory (2h)**: Learn containers, images, Docker architecture via [TechWorld with Nana](https://www.youtube.com/c/TechWorldwithNana).
- **Practice (3h)**: Install Docker, run `nginx`, use `docker ps`, `docker run`.
- **Review (1h)**: Write Docker cheat sheet.

### Day 16: Dockerfiles
- **Theory (2h)**: Study Dockerfile syntax, best practices.
- **Practice (3h)**: Write Dockerfile for Python app, build/run it.
- **Review (1h)**: Optimize Dockerfile.

### Day 17: Docker Compose
- **Theory (2h)**: Learn multi-container apps with Docker Compose.
- **Practice (3h)**: Create Compose file for Flask + PostgreSQL.
- **Review (1h)**: Debug Compose issues.

### Day 18: Kubernetes Basics
- **Theory (2h)**: Learn pods, deployments, services via [Kube by Example](https://kubebyexample.com/).
- **Practice (3h)**: Install Minikube, deploy `nginx`.
- **Review (1h)**: Explain pods vs. containers.

### Day 19: Kubernetes Advanced
- **Theory (2h)**: Study ConfigMaps, Secrets, scaling.
- **Practice (3h)**: Scale `nginx` deployment, add ConfigMap.
- **Review (1h)**: Document scaling steps.

### Day 20: Kubernetes CI/CD
- **Theory (2h)**: Learn Kubernetes deployment via CI/CD.
- **Practice (3h)**: Use GitHub Actions to build Docker image, deploy to Minikube.
- **Review (1h)**: Troubleshoot deployment.

### Day 21: Mini Project + Review
- **Project (4h)**: Containerize web app, deploy to Minikube with CI/CD.
- **Review (2h)**: Polish project, revisit Docker/K8s.

---

## Week 4: Monitoring, Security, and Polish (Days 22-30)
**Goal**: Add monitoring, security, and a capstone project.  
**Daily Commitment**: 6h (~2h theory, 3h practice, 1h review).

### Day 22: Monitoring Basics
- **Theory (2h)**: Learn Prometheus and Grafana basics.
- **Practice (3h)**: Set up Prometheus for Docker app, visualize with Grafana.
- **Review (1h)**: Explain tracked metrics.

### Day 23: Logging
- **Theory (2h)**: Study centralized logging (ELK or Loki).
- **Practice (3h)**: Set up logging with Loki or file-based solution.
- **Review (1h)**: Document log setup.

### Day 24: Security Basics
- **Theory (2h)**: Learn SSH keys, firewalls, secrets management.
- **Practice (3h)**: Secure EC2 (disable root, add SSH key), use AWS Secrets Manager.
- **Review (1h)**: List 5 security best practices.

### Day 25-29: Capstone Project
- **Project (5h/day, 25h total)**: Build a full pipeline:
  - Deploy Node.js app to EC2 or Kubernetes.
  - Use Terraform, Docker, GitHub Actions.
  - Add Prometheus/Grafana and logging.
- **Review (1h/day)**: Document progress, troubleshoot.

### Day 30: Review and Next Steps
- **Review (4h)**: Refine projects, create GitHub portfolio README.
- **Planning (2h)**: Research DevOps jobs, identify gaps (e.g., Ansible, advanced K8s).

---

## Tools/Resources
- **Free Learning**: YouTube (TechWorld with Nana, freeCodeCamp), Linux Journey, AWS Free Tier, Terraform docs.
- **Practice**: VirtualBox, Minikube, GitHub, AWS/GCP free tiers.
- **Portfolio**: Host projects on GitHub with READMEs.