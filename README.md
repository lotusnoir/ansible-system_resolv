# ansible-system_resolv

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_resolv-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_resolv)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_resolv.svg)](https://github.com/lotusnoir/ansible-system_resolv/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_resolv?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_resolv)
[![downloads](https://img.shields.io/ansible/role/d/56930)](https://galaxy.ansible.com/lotusnoir/system_resolv)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/56930)](https://galaxy.ansible.com/lotusnoir/system_resolv)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Configure resolv.conf

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_resolv
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_resolv


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
