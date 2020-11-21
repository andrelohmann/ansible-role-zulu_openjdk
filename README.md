zulu_openjdk
============

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-zulu_openjdk.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-zulu_openjdk)

Use this role to install OpenJDK from zulu ppa.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    zulu_openjdk_version: "15"

Find available Versions [here](https://docs.azul.com/zulu/zuludocs/ZuluUserGuide/InstallingZulu/InstallOnLinuxUsingDebRepository.htm).

15, 13, 11, 8, or 7 at the time of writing.

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
