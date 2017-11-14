[![Build Status](https://travis-ci.org/NINEJKH/ansible-role-nullmailer.svg?branch=master)](https://travis-ci.org/NINEJKH/ansible-role-nullmailer)

# ninejkh.nullmailer

An Ansible role that installs nullmailer 2.x (from source) on Debian-like systems.

## Requirements

none

## Role Variables

```yaml
nullmailer_version: 2.1
```

## Dependencies

none

## Example Playbook

```yaml

- hosts: nullmailer
  roles:
    - { role: ninejkh.nullmailer }
```

## License

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.

## Author Information

[9JKH (Pty) Ltd.](https://9jkh.co.za)
