Role Name
=========

Installs Nagios nrpe client and okconfig.

Role Variables
--------------

A description of the settable variables for this role should go here, including
any variables that are in defaults/main.yml, vars/main.yml, and any variables
that can/should be set via parameters to the role. Any variables that are read
from other roles and/or the global scope (ie. hostvars, group vars, etc.) should
be mentioned here as well.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: okh_nagios_client

    - hosts: servers
      roles:
         - { role: okh_nagios_client, allowed_hosts: '127.0.0.1,94.142.159.1,94.142.159.26,94.142.159.5' }

License
-------

GPLv3
