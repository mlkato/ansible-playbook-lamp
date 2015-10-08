# ansible-playbook-lamp
Ansible Playbook for CentoOS 6.7

# Requirements
- Vagrant
- VirtualBox
- Python
- Ansible

# About Vagrant Box
- CentOS 6.7
- vagrant-vbguest

# About Playbooks

Provisioning Linux, Apache, Mysql, PHP (a.k.a. lamp) environment.  
In addition, install swfmill (ver 0.3.x) for Flash.

# How to Use

```
1. $ vagrant up --no-provision
2. $ vagrant provision
3. $ SUDO passward: vagrant
```

:zap: **Caution** :zap:  
Don't just run `vagrant up` 'cause provisioning silently failed.  
If you just run `vagrant up`, `ps` to file ansible process and kill it.  
Contribution is welcome!!
