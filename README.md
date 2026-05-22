# Learning Ansible - Code Examples & Playbooks

This repository contains code examples, inventory configurations, and automation playbooks from the book **"Running Ansible" (Запускаем Ansible)** by Lorin Hochstein, René Moser, and Bruno Meier (Published in Russian in 2023).

The examples track the journey of automating server configuration, application deployment, and orchestration from the ground up—covering basic ad-hoc commands, syntax, variables, roles, vault security, and production-grade infrastructure automation.

## 🚀 Repository Structure

The repository is organized by chapters, following the logical progression of the book:

```text
.
├── README.md
├── ch01-introduction/              # Overview of Ansible architecture and core concepts
├── ch02-getting-started/           # Initial setup, SSH configurations, and Ad-Hoc commands
├── ch03-playbooks/                 # Writing first playbooks, tasks, and YAML syntax
├── ch04-variables-facts/          # Using variables, facts gathering, and magic variables
├── ch05-control-flow/             # Conditionals (when), loops (loop, with_items), and handlers
├── ch06-roles/                    # Structuring reusable automation components with Ansible Roles
├── ch07-ansible-vault/            # Encrypting sensitive data, secrets, and passwords
├── ch08-complex-playbooks/        # Complex deployments, templates (Jinja2), and filters
└── ch09-production-practices/     # Optimizing performance, parallelism, and troubleshooting