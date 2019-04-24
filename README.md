andrewrothstein.openjdk
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-openjdk.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-openjdk)

Installs [OpenJDK](https://jdk.java.net/)

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.openjdk
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
