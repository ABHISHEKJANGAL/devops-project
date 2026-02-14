# DevOps Practice Project

This repository contains:

✅ Ansible playbook to install Apache2 & Git  
✅ Jenkins pipeline definition to automate this setup

## How It Works

1. Jenkins pipeline pulls this repo
2. Jenkins executes the Ansible playbook
3. The playbook installs:
   - Git
   - Apache2
   - A sample HTML page

## Files

- `setup.yml` — Ansible playbook  
- `Jenkinsfile` — Jenkins CI/CD pipeline  
