rompe.firewalld
===============

A simple Ansible role that makes sure firewalld and its Python module are installed and running.

Requirements
------------

Tested on CentOS and Raspbian.

Role Variables
--------------

n/a

Dependencies
------------

n/a

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: rompe.firewalld, tags: firewall }

License
-------

MIT

Author Information
------------------

Created by Ulf Rompe  2019
