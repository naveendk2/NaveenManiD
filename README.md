# Apache Web Server Automation using Ansible

### 👤 Author: Naveen Mani D

---

## 📘 Project Overview

This project automates the installation and configuration of the **Apache web server** on Linux systems using **Ansible**. It showcases **Infrastructure as Code (IaC)** principles by enabling consistent, repeatable, and scalable web server deployments across environments.

---

## 🛠️ Tools & Technologies

- 🐧 Linux (Ubuntu/CentOS)
- ⚙️ Ansible
- 📄 YAML
- 🧑‍💻 Git & GitHub

---
```
## 📂 Project Structure


apache-ansible/
├── apache.yml # Ansible playbook to install and configure Apache
├── inventory # Inventory file (local or remote hosts)
├── index.html # Sample HTML page to deploy
└── README.md # Project documentation

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/YourUsername/apache-ansible.git
   cd apache-ansible
2. ansible-playbook -i inventory apache.yml
```



