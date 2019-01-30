packer
======

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-packer.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-packer)

Use this role to install packer.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    packer_version: 1.3.3

Example Playbook
----------------

    - hosts: packer
      roles:
         - { role: andrelohmann.packer }

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
