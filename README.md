# Ansible Utils

Utils playbooks to setup differents useful tools on servers. Tested on Debian 11 with Ansible core  2.13.4

# Usage

You can edit [ansible.cfg](./ansible.cfg) and [hosts](./hosts) files with your own specifications (ssh keys, users, hosts...)

Now install all the roles using 
```
ansible-galaxy install -r requirements.yml
```

When everything is configured you can now launch the playbook you want using 
```
ansible-playbook playbook/{playbook_name}.yml
```
