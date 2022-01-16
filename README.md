Ansible-role-mailserver
=========

This role is based on the steps mentioned in his blog post by Thomas Leister. https://thomas-leister.de/mailserver-debian-buster/
It describes how to setup an Mailserver on Debian Buster.

Requirements
------------

- Installation of a Debian 10 System
  - separate partition for postbox directory (/var/vmail)

TODO: Change and test with a newer Debian Version 

Role Variables
--------------

Dependencies
------------

Created without dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

GPLv3

Author Information
------------------

Contact: cfl+ansible@fluegel.it
