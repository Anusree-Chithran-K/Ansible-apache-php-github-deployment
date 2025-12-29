# Automated WordPress Deployment with Ansible

## Tech Stack
- Ansible
- Apache
- MariaDB
- PHP
- WordPress
- Amazon Linux / CentOS

## What this project does
- Installs Apache, PHP, MariaDB
- Secures MariaDB (removes test DB, anonymous users)
- Creates WordPress database & user
- Deploys WordPress automatically
- Configures Apache Virtual Host
- Uses Jinja2 templates for configuration

## How to run
ansible-playbook -i hosts playbook.yaml

## Security Notes
- Passwords are placeholders
- Use Ansible Vault for production
