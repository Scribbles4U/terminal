# Ansible Init

## Usage

```
ansible-playbook -i inventory.ini playbook.yaml --extra-vars "ansible_ssh_user=<USER>" --ask-become-pass --limit "<HOST>"
```

## To Do
* Create or adapt existing playbook for MacOS (currently setup for Linux)
* Add tasks to install ~/.p10k.zsh to avoid having to wizard at login
