Role Name
=========

Configure anacron

Requirements
------------

n/a

Role Variables
--------------

 * anacron_start_hours_range: "3-22"

Dependencies
------------

n/a

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: adherzog.anacron }

License
-------

BSD
