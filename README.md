# Ansible-Based Docker & Kubernetes Deployment

This project automates the entire workflow of deploying dockerized Web App by building a Docker image, pushing it to Docker Hub, and deploying it to a Kubernetes cluster using Ansible.

## 🚀 Project Structure
ansible-k8s-web_app
├── ansible/ # Contains Ansible playbook and variables
│ ├── playbook.yml
│ └── vars.yml
├── k8s/ # Contains Kubernetes manifest templates
│ ├── deploy.yml.j2
│ └── service.yml.j2
└── web_app/ # Flask Web App (app.py, Dockerfile, requirements.txt)


[LinkedIn url]()

