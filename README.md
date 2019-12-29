# Ansible config playbook for Ubuntu 18.04 workstation
Ansible setup for my study and dev laptop

## Install Ansible on workstation
```
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
```

## Pull config to workstation
```
sudo ansible-pull -U https://github.com/mindrenee/Ansible.git
```
