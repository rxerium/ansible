# Ansible Scripts

A personal list of playbooks I use with Ansible in my Homelab, all of which is managed in [Ansible Semaphore](https://www.ansible-semaphore.com/).

![alt text](/misc/ansible-dalle.png)

# Overview

## Inventory

Currently I am utilsiing GitHub Actions to create dynamic inventories, the Action will use Nmap to scan all host on the 10.0.30.0 subnet and return active hosts then add additional usernames where appicable. 

## Playbooks

Playbooks are organised into their respective folders:
- docker
- fileManagement
- misc
- securtyHardening
- userManagement

# Contact

If you have any questions feel free to reach out to me on [Signal](https://signal.me/#eu/0Qd68U1ivXNdWCF4hf70UYFo7tB0w-GQqFpYcyV6-yr4exn2SclB6bFeP7wTAxQw) or via email: rishi@rxerium.com.