[![](https://github.com/ansible-roles-matsumura/beer-mug/workflows/Build/badge.svg)](https://github.com/ansible-roles-matsumura/beer-mug/actions)

Role Description
=========

Installs [beer-mug](https://github.com/misoton665/beer-mug) for CentOS7.

Requirements
------------

EPEL installed before running this role.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - geerlingguy.repo-epel
    - beer-mug
```

License
-------

BSD
