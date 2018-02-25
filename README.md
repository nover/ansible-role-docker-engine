# Ansible role for Docker Engine

This role installs Docker Engine on Ubuntu 14.04 and 16.04

## Requirements

No Requirements

## Role Variables

 - `arch` - the system architecture to install for, valid values are `amd64` and `armhf`

## Dependencies

No external dependencies

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: nover.docker-engine }

## License

The unlicense