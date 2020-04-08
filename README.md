devinbarry.anaconda
=========

A role that installs [Anaconda](https://www.continuum.io/anaconda-overview) as the specified user in the
default location as you might install it yourself following the default instructions.

Based upon [andrewrothstein.anaconda](https://github.com/andrewrothstein/ansible-anaconda)

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
    - devinbarry.anaconda
```

License
-------

GPL v3

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
