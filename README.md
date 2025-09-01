 DevOps E2E Project

This project demonstrates an end-to-end DevOps pipeline using Terraform, Ansible, Python, Jenkins, AWS, Kubernetes, and Docker.
The goal is to show how different DevOps tools work together to automate infrastructure, configuration, validation, and deployment.

---

🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)




---








<div style="border-top: 4px solid black; margin: 30px 0;"></div>
 Project Overview

This project ties together infrastructure provisioning, configuration management, validation, and CI/CD automation into a single workflow.

🔑 Key Features

Terraform creates AWS EKS clusters

Ansible automates node configuration (placeholder in this repo)

Python validates variables/configurations

Jenkins runs the pipeline end-to-end

AWS + Kubernetes + Docker for scalable cloud deployments


---

📂 Project Structure
devops-e2e/
├── backend.tf      # Terraform backend configuration  
├── main.tf         # Terraform infrastructure (AWS EKS cluster)  
├── playbook.yml    # Ansible playbook (placeholder for node config)  
├── validate.py     # Python validation script (placeholder for variable checks)  
├── Jenkinsfile     # CI/CD pipeline definition  
└── README.md       # Documentation  

---

⚙️ Setup & Run
1. Clone the Repository
git clone <repo-url>
cd <repo-folder>

---

2. Run Terraform
terraform init
terraform apply --auto-approve

---

3. Run Python Validation
python3 validate.py

---

4️.  Run Ansible Playbook
ansible-playbook playbook.yml

---

5. Jenkins Pipeline

Runs Python validation

Runs Ansible playbook

Applies Terraform provisioning

---


✅ Problems & Solutions
Terraform

Problem (Before): Setting up infrastructure like EKS clusters manually on AWS was time-consuming and error-prone.
Solution (Now): Terraform automates infrastructure creation with code (Infrastructure as Code).

Ansible

Problem (Before): Nodes had to be configured manually.
Solution (Now): Ansible automates configuration (placeholder here).

Python

Problem (Before): No quick way to validate variables before deploying.
Solution (Now): Python script validates variables/configs to prevent mistakes.

Jenkins

Problem (Before): Running steps manually was slow and error-prone.
Solution (Now): Jenkins automates the workflow in a pipeline.

AWS + Kubernetes + Docker

Problem (Before): Running apps only locally limited scalability.
Solution (Now): Cloud-native stack provides scalability, consistency, and reliability.

---


 What I Learned:

Terraform for infrastructure automation

Ansible for configuration management

Python for validation scripting

Jenkins for CI/CD orchestration

How AWS, Kubernetes, and Docker integrate in modern DevOps workflows


---
