# Ansible recipe

Ansible playbook for centos 7. create start web with basic variables

### Configure your server

```bash
#add -> your-ip ansible-user=your-user
vim /etc/ansible/hosts
```

### What's inside?
- nginx
- nginx virtualhost template
- variables in main.yml
- php 7.2

### Clone repository

```
git clone git@github.com:juanpablocs/ansible-php7.2.git
cd ansible-php7.2
```

### Execute ansible playbook
```
ansible-playbook main.yml
```
