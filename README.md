# Ansible recipe

Configure your server

```
#add -> your-ip ansible-user=your-user
vim /etc/ansible/hosts
```

Clone repository

```
git clone git@github.com:juanpablocs/ansible-php7.2.git
cd ansible-php7.2
```

Execute ansible playbook
```
ansible-playbook main.yml
```
