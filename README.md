andrewrothstein.jupyter-profile
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-jupyter-profile.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-jupyter-profile)

* Installs and configures a [Jupyter](https://jupyter.org/) notebook
* Assumes [Anaconda](https://www.continuum.io/anaconda-overview) is installed.

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
    - andrewrothstein.jupyter-profile
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
