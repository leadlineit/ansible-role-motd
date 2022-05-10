# Ansible Galaxy Role Motd

![Build Status](https://github.com/leadlineit/ansible-role-motd/actions/workflows/ansible-galaxy-ci.yml/badge.svg)
[![Galaxy Role](https://img.shields.io/badge/Ansible--Galaxy-leadlineit.motd-blue.svg?logo=ansible&logoColor=white)](https://galaxy.ansible.com/leadlineit/motd/)

This role helps to manage motd package for Debian(stretch/buster/bullseye).

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
    - { role: leadlineit.motd, tags: motd }
```

License
-------

MIT

Author Information
------------------

This role was created by Stas Stavnichuk.
