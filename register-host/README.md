Role Name
=========

This role will uses a API which is used to add the host to the Nagios XI and a API which will add basic linux services to the host

Requirements
------------

You need to have NRPE client installed on the systems and ansible machine to be connected with the NAGIOS xi server

Role Variables
--------------


Nagios XI ip  address and API key 

Dependencies
------------

None

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
