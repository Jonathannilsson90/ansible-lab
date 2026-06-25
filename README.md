# Ansible lab

## Introduction

Reasoning behind this project was to gain a basic understanding about Ansible.

## Installation and basic labs

- Followed this guide to get a basic understanding of installation and basic commands locally. [Basics to Ansible](https://docs.ansible.com/projects/ansible/latest/getting_started/index.html/)

## Basic commands

Activate keyagent:

```bash eval $(ssh-agent)
ssh-add /root/.ssh/id_ed25519
```

Docker:

- `docker compose up -d --build`
- `docker stop $(docker ps -q)`

Ansible:

- `ansible myhosts -m ping -i inventory.ini`
- `ansible-inventory -i inventory.ini --list`
- `ansible-playbook`
