ansible-wifi
============

Ansible playbook for a wireless access point

Setup
-----

```sh
$ git clone https://github.com/dceoy/ansible-wifi.git
$ cd ansible-wifi
$ cp example_hosts hosts
$ vim hosts       # => edit
```

Usage
-----

Provision a wireless access point

```sh
$ ansible-playbook -i hosts sync.yml
```
