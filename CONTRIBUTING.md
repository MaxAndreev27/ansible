# Contributing Guidelines

Thank you for considering contributing to this repository! We welcome contributions, bug fixes, documentation improvements, and new feature additions.

## How to Contribute

1. **Fork the Repository**: Create your own fork of the project on GitHub.
2. **Clone the Repository**: Clone your fork locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/ansible.git
   cd ansible
   ```
3. **Create a Feature Branch**: Create a descriptive branch name for your changes:
   ```bash
   git checkout -b feature/my-new-feature
   ```
4. **Make Your Changes**:
   - Ensure code adherence to Ansible best practices.
   - Run `yamllint .` to check YAML formatting.
   - Verify playbooks with `ansible-lint` if available.
   - Test playbooks using Vagrant (`vagrant up`, `ansible-playbook -i inventory/vagrant.ini ...`).
5. **Commit Your Changes**: Keep commit messages clear and concise:
   ```bash
   git commit -m "Add feature: detailed description of changes"
   ```
6. **Push to GitHub**: Push your branch to your fork:
   ```bash
   git push origin feature/my-new-feature
   ```
7. **Open a Pull Request**: Submit a Pull Request against the `main` branch of the original repository.

## Code Style & Standards

- **YAML Formatting**: Use 2 spaces for indentation in YAML files. Do not use tabs.
- **Ansible Best Practices**:
  - Name all tasks clearly (`name: ...`).
  - Keep sensitive data out of plain text (use Ansible Vault if needed).
  - Use modular and reusable patterns.

## Community Standards

Please note that this project is released with a [Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project, you agree to abide by its terms.
