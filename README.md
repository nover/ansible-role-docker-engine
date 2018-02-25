# Ansible role for Docker Engine

This role installs Docker Engine on Ubuntu 14.04, 16.04 and Debian Stretch variants

## Requirements

No Requirements

## Role Variables

 - `docker_arch` - the system architecture to install for, valid values are `amd64` and `armhf`
 - `docker_channel` - the docker ce channel to use, valid values are `stable` and `edge`

## Dependencies

No external dependencies

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: nover.docker-engine }

## License

The unlicense