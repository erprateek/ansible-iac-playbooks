# Ansible Dev Environment Playbooks

This repository contains Ansible playbooks to bootstrap Ubuntu systems for:

- 📊 Data Science & Machine Learning
- 🧠 LLM-driven Application Development

## 🛠️ Usage

### 1. Set up your inventory

Edit `inventory/hosts.ini` with the IPs or hostnames of your target machines.

### 2. Run a playbook

```bash
ansible-playbook -i inventory/hosts.ini playbooks/data-science.yml -u <username> --ask-become-pass
```
```bash
ansible-playbook -i inventory/hosts.ini playbooks/llm-dev.yml -u <username> --ask-become-pass
```
### 3. Requirements

```bash
pip install ansible
```
