zulu_openjdk
============

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-zulu_openjdk.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-zulu_openjdk)

Use this role to install OpenJDK from zulu ppa.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    zulu_openjdk_version: "12"

Example Playbook
----------------

    - hosts: zulu_openjdk
      roles:
         - { role: andrelohmann.zulu_openjdk }

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
