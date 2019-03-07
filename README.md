[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-vsftpd.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-vsftpd)
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
    - iac-ansible-vsftpd
...    
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
