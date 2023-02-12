[![GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-BE0000?style=plastic)](#)  
[![Rocky Linux](https://img.shields.io/badge/RockyLinux-07BA82?style=plastic)](#) [![Ubuntu+](https://img.shields.io/badge/Ubuntu-DD4814?style=plastic)](#) [![Raspberry Pi OS](https://img.shields.io/badge/Raspberry--Pi--OS-C51A4A?style=plastic)](#)  
[![Ansible](https://img.shields.io/badge/Ansible-131211?style=plastic)](#) [![Python 3](https://img.shields.io/badge/Python-3-3673A5?style=plastic)](#)  

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
| 5 | linux-mariadb  | To setup MariaDB for RockyLinux.  |
  
