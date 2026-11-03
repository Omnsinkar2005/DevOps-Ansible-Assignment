# ShopEase - DevOps Automation Project

## Project Overview
ShopEase is a sample e-commerce website used to demonstrate the practical implementation of DevOps concepts.

This project demonstrates automated web server installation and website deployment using Ansible and Nginx on Ubuntu 22.04.

## Technologies Used
- Ubuntu 22.04
- Ansible
- Nginx
- HTML and CSS
- Git and GitHub
- Windows Subsystem for Linux (WSL2)

## Project Structure

DevOps-Ansible-Assignment/
├── documentation/
│   ├── devops_lifecycle.md
│
└── ansible/
    ├── inventory.ini
    ├── site.yaml
    └── files/
        └── index.html

## Practical Implementation

1. Configured Ubuntu using WSL2.
2. Installed Ansible.
3. Created an Ansible inventory.
4. Created a sample ShopEase e-commerce website.
5. Developed an Ansible playbook.
6. Installed and configured Nginx.
7. Deployed the website automatically.
8. Tested Ansible idempotency.
9. Modified the website and redeployed it through Ansible.

## Deployment Commands

Check playbook syntax:

ansible-playbook -i ansible/inventory.ini ansible/site.yaml 


Execute deployment:

ansible-playbook -i ansible/inventory.ini ansible/site.yaml

Verify Nginx:

sudo systemctl status nginx

Access the website:

http://localhost

## Scope

The practical implementation covers Ansible-based configuration management and Nginx website deployment.

GitHub Actions, Prometheus and Grafana are discussed as part of the proposed DevOps workflow, but are not implemented in this practical demonstration.

## Author
Om Sinkar
