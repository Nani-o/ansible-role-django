[![Build Status](https://travis-ci.org/Nani-o/ansible-role-django.svg?branch=master)](https://travis-ci.org/Nani-o/ansible-role-django)

django
======

A role for installing and managing django install along with app deployment.

Compatibility
-------------

  - CentOS 6
  - CentOS 7
  - Ubuntu 14.04
  - Ubuntu 16.04
  - Debian 8
  - Debian 9

Role Variables
--------------

- django_projects

A list of django projects that you want to install.

```YAML
django_projects:
  - root: /path/to/myapp
    user: myapp
  - root: /path/to/myapp2
    user: myapp2
```

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-role-django }

License
-------

MIT

Author Information
------------------

Sofiane MEDJKOUNE
