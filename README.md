[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-jupyter-profile.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-jupyter-profile)
andrewrothstein.jupyter-profile
=========

Installs [Jupyter](https://jupyter.org/) atop [Anaconda](https://www.continuum.io/anaconda-overview)

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
