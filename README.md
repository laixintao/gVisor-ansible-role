gVisor
======

Use [gVisor](https://github.com/google/gvisor)'s runsc as docker's runtime. Make docker container a safer sandbox.

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
