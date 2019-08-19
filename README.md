Ansible-Bitwarden
=========

[![Build Status](https://travis-ci.org/artis3n/bitwarden-app.svg?branch=master)](https://travis-ci.org/artis3n/bitwarden-app)

This role installs the latest version of the Bitwarden .deb from Github. The Bitwarden deb does not auto-update, so this role can be used to install the latest version.

Requirements
------------

- Python 3
- Pipenv (`pip3 install pipenv`)

Set up the project dependencies:
`pipenv install`

Role Variables
--------------

None. You will always install the latest version of Bitwarden, by design.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: bitwarden_app }

License
-------

BSD, MIT

Author Information
------------------

[Artis3n](https://galaxy.ansible.com/artis3n)
