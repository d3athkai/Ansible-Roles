![GitHub](https://img.shields.io/badge/license-GPL--3.0-orange?style=plastic) ![GitHub](https://img.shields.io/badge/Python-2.7+-green?style=plastic) ![GitHub](https://img.shields.io/badge/Ansible-2.9+-blue?style=plastic) 

# My Ansible Roles
A Work-in-Progress (WIP), with more Ansible Roles adding regularly.  
  
## Ansible Tips and Tricks
Refer to [My Ansible Tips and Tricks](https://gist.github.com/d3athkai/3b1c6becc41d79f45332f238791ceb3d).  
  
# Recommended Ansible Settings
In `/etc/ansible/ansible.cfg`, under `[defaults]`, add: `interpreter_python=/usr/bin/python3`
   
## Roles List
| S/N  | Role  | Description  |
| ------------- | ------------- | ------------- |
| 1 | linux-updates  | To perform OS Updates for RockyLinux / Red Hat / Ubuntu / Debian / Raspberry Pi OS.<br>It will reboot the host after updating and wait for the host to boot.<br>It has the options of enabling logging for both available updates and installed updates in the logging directory specified.  |
| 2 | linux-fail2ban  | To setup Fail2ban for RockyLinux / Ubuntu / Debian / Raspberry Pi OS.<br>Multiple failed ssh attempts will result in IP block in UFW / Firewalld.  |
| 3 | linux-docker  | To setup Docker for RockyLinux / Ubuntu / Debian / Raspberry Pi OS.<br>It has the options of creating a user to manage Docker and installing Docker Compose.  |
| 4 | linux-sssd  | To setup SSSD for RockyLinux / Ubuntu / Debian / Raspberry Pi OS.  |
  
