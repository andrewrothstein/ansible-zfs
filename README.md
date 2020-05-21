andrewrothstein.zfs
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-zfs.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-zfs)

Installs [OpenZFS on Linux](https://github.com/openzfs/zfs/wiki)

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
    - andrewrothstein.zfs
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
