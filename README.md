# Ansible_course

This is ansible-play for installing apache2 with the ability to select and install a new version of php

## How to start
Add ip, username and password in *host_vars*.
```
ansible-playbook playbooks_basic/roles.yaml -i hosts -K -v
```
Enter the sudo password!

## How to check
![example](https://user-images.githubusercontent.com/57665335/163481988-bb2e9fb2-2a13-4398-8f12-e6f1059cd84a.png)
