Role Name
=========

A brief description of the role goes here.

Requirements
------------

docker

(Recommand https://github.com/geerlingguy/ansible-role-docker ).

Role Variables
--------------

None.

Dependencies
------------

docker

Example Playbook
----------------

```
- hosts: servers
  roles:
     - docker
     - gvisor
```

Use gVisor's runsc as docker's runtime:

```
todo
```

License
-------

BSD

Author Information
------------------

laixintao.
