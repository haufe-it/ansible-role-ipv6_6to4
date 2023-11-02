Role Name
=========

**WARNING**

**INCOMPLETE** - **WORK IN PROGRESS**

Configure 6to4 on a machine having a public IPv4 address

Requirements
------------

- Debian
- public IPv4 address

Role Variables
--------------

- interface: WAN interface to use public IP from

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: username.rolename, interface: wan0 }

License
-------

GPL-3.0-only

Author Information
------------------

Jakob Haufe <jakob@haufe.it>
