# ansible-system_resolv

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_resolv-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_resolv)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_resolv.svg)](https://github.com/lotusnoir/ansible-system_resolv/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_resolv?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56111)](https://galaxy.ansible.com/lotusnoir/system_resolv)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56111)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)


Comfigure resolv.conf using ansible.

## Requirements

none

## Role variables

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|

## Examples

        ---
        - hosts: system_resolv
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-system_resolv
          environment:
            http_proxy: "{{ http_proxy }}"
            https_proxy: "{{ https_proxy }}"
            no_proxy: "{{ no_proxy }}

## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

