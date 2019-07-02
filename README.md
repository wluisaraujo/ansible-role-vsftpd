[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-vsFTP%20Server-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-vsftpd) [![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-vsftpd.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-vsftpd)

---
# IaC: with [Ansible](https://www.ansible) role to install and configure [Vsftp FTP Server](vsftpd.beasts.org/)
------------

Description
------------

 *

Requirements
------------

 *

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
