# ansible-role-apt

[![Build Status](https://travis-ci.org/kosssi/ansible-role-apt.svg?branch=master)](https://travis-ci.org/kosssi/ansible-role-apt)

Ansible role for execute apt-get update and install apt-repositories and apt-packages.

## Role Defaults Variables

    apt_cache_valid_time: 3600
    apt_upgrade: true
    apt_upgrade_type: safe          # safe, full or dist
    apt_install:
      - python-apt
      - unattended-upgrades
    apt_repositories: false

## Example Playbook

      roles:
        - { role: kosssi.composer }

## License

MIT
