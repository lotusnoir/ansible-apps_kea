# ansible-apps_kea

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_kea-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_kea)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_kea.svg)](https://github.com/lotusnoir/ansible-apps_kea/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_kea?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56104)](https://galaxy.ansible.com/lotusnoir/apps_kea)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56104)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Install and configure server dhcp kea

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_kea
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_kea


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.
