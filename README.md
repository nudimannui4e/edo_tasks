# Edo Task
## Ansible playbooks 
### with 7 roles
- ansible_keys
- apt_conf
- chrony
- grub_conf
- postgresql
- soft_min
- users_create

## Example playbook (postgesql roles)
```
---
- name: PostgreSQL 12
  hosts: localhost
  roles:
    - postgresql
```
```
ansible-playbook postgresql.yml
```
