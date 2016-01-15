Repo\_remi
=========

Role install remi repository from http://blog.remirepo.net/. Useful for mote php versions on RHEL and clones.

Requirements
------------

Works only on RedHat like systems.

Dependencies
------------

Epel repository must be available.

Role Variables
--------------

state: 
  - present: Ensure repository is available (default)
  - absent: Ensure repository is not available.

Example Playbook
----------------

    - hosts: rhel_servers
      roles:
         - { role: davidkarban.repo_remi }

License
-------

GPLv3

Author Information
------------------

email: david@karban.eu

github: davidkarban

web: www.karban.eu

