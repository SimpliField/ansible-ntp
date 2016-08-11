Ntp [![Build Status](https://travis-ci.org/SimpliField/ansible-ntp.svg?branch=master)](https://travis-ci.org/SimpliField/ansible-ntp) [![Ansible Role](https://img.shields.io/ansible/role/11473.svg?maxAge=2592000)](https://galaxy.ansible.com/SimpliField/ntp/)
=========

Setup Ntp to sync time.

If you use systemd your should look at `timesyncd`.

Requirements
------------

Need ansible 2

Role Variables
--------------


Dependencies
------------

There is no dependencies

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
   - { role: SimpliField.ntp }
```

License
-------

BSD
