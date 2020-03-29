# ansible-role-traefik
Ansible role. Install and configure traefik.

Traefik is a reverse-proxy: https://docs.traefik.io/

Traefik IHM is accessible with: http://traefik.ansible-test.local

## Installation

For now, only docker-compose install is able.


## Run tests

`ansible-playbook -i tests/hosts tests/test.yml --limit localhost`

## Configuration

Check `defaults/main.yml`

## Examples

Check `tests/test.yml`.