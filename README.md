ansible-role-home-assistant
======================

This role configures home assistant for my homelab.

Requirements
------------

N/A

Role Variables
--------------
* home\_assistant\_trusted\_proxy

Role Defaults
-------------
* home\_assistant\_conf\_dir
* home\_assistant\_user
* home\_assistant\_group

N/A

Dependencies
------------

N/A

Example Playbook
----------------

```
- hosts: servers
  roles:
    - ansible-role-home-assistant
```

License
-------

MIT

Author Information
------------------

I can be reached at [djm@murrayfoundry.com](mailto:djm@murrayfoundry.com).
