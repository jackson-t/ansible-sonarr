ansible-sonarr
=========

This role will install Sonarr v3 onto Ubuntu 18.04

Requirements
------------

None

Role Variables
--------------

Variables are primarily from the sonarr config file. See [config.xml](templates/config.xml) and the [defaults](defaults/main.yml).

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-sonarr }

License
-------

BSD

Author Information
------------------

This role was created in 2019 by Jackson.

