Ansible role: RPM Fusion
=========

[![CI](https://github.com/xiple/ansible-role-rpmfusion/actions/workflows/ci.yml/badge.svg)](https://github.com/xiple/ansible-role-rpmfusion/actions/workflows/ci.yml)

An ansible role that installs RPM Fusion free & nonfree repositories.

Requirements
----------------

None.

Role Variables
----------------

None.

Supported distributions
----------------

This role has been been developed and tested on Fedora 42, 43 and 44.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - xiple.rpmfusion
```

License
-------

MIT
