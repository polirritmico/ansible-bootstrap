# Develop Environment Bootstrap Installer

## Script

```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/polirritmico/ansible_bootstrap/main/bootstrap_install)"
```

## Description

This script installs the necessary packages and sets up my custom environment by
cloning a private repository using a `PAT` token and executing an `Ansible`
playbook.

## Supported systems

> - [x] Arch Linux
> - [x] Fedora
> - [ ] Gentoo (not tested)
> - [x] Ubuntu
