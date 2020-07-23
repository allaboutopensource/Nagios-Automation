Role Name
=========

This role will uses a API which will remove services from the host and an API which will remove the host from the Nagios XI database.


Requirements
------------

There should be connection from the ansoble machine to the Nagios XI server for the API to perform the task.

Role Variables
--------------

Nagios XI ip  address and API key 

Dependencies
------------
None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
