# macOS Ansible Playbook

This Ansible playbook installs and configure my macOS for web development. The packages and apps that I use are defined in `vars/installs.yml`.

## Installation
- Install Homebrew
- Install Ansible `brew install ansible`
- Install requirements `ansible-galaxy install -r requirements.yml`
- Sign in App Store

## Run
- Run playbook `ansible-playbook main.yml --ask-become-pass`

## Inspired by

- https://github.com/geerlingguy/mac-dev-playbook
- https://github.com/opdavies/macos-provisioning
- https://github.com/dotCipher/workstation-playbooks/blob/master/ansible/tasks/fish-shell.yml
- https://github.com/geerlingguy/ansible-role-php-pecl
