# routinator
Ansible roles for deploying Routinator

## General

This repository an Ansible playbook defining a role to deploy [Routinator 3000](https://github.com/NLnetLabs/routinator).

What you will get:
- Routinator 3000
- rsyslog
- A systemd service to get things going

References: 
- Routinator: https://github.com/NLnetLabs/routinator/releases

## Validating the validators
The role will set up its validator as a systemd service, so you can check the status with `sudo systemctl status routinator`. 

Connect your routing equipment to the RTR port (8282 by default) and begin validating your routes!