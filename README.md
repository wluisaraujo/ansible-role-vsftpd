[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-vsFTP%20Server-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-vsftpd) [![Build Status](https://travis-ci.com/wluisaraujo/ansible-role-vsftpd.svg?branch=master)](https://travis-ci.com/wluisaraujo/ansible-role-vsftpd)

---
# IaC: with [Ansible](https://www.ansible) role to install and configure [Vsftp FTP Server](vsftpd.beasts.org/)
------------

Description
------------

 *

Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.vsftpd
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.vsftpd/requirements.txt
```

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - vsftpd
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
