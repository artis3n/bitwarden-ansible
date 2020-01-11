# Ansible-Bitwarden

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/artis3n/bitwarden-app/Molecule%20Tests)](https://github.com/artis3n/bitwarden-app/actions)
[![Ansible Role](https://img.shields.io/ansible/role/42458)](https://galaxy.ansible.com/artis3n/bitwarden_app)
[![Ansible Role](https://img.shields.io/ansible/role/d/42458)](https://galaxy.ansible.com/artis3n/bitwarden_app)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/42458)](https://galaxy.ansible.com/artis3n/bitwarden_app)
![GitHub](https://img.shields.io/github/license/artis3n/bitwarden-app)
![GitHub followers](https://img.shields.io/github/followers/artis3n?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/artis3n?style=social)

This role installs the latest version of the Bitwarden .deb from GitHub. The Bitwarden .deb does not auto-update so this role can be used to install the latest version.

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
        - role: bitwarden-app

License
-------

MIT

Author Information
------------------

[Artis3n](https://galaxy.ansible.com/artis3n)
