Ntp
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
