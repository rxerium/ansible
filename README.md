# Ansible Scripts

A personal list of playbooks I use with Ansible in my Homelab, all of which is managed in [Ansible Semaphore](https://www.ansible-semaphore.com/).

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

