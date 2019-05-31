andrewrothstein.bash-it
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-bash-it.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-bash-it)

Installs bash and [bash-it](https://github.com/Bash-it/bash-it)

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
    - andrewrothstein.bash-it
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
