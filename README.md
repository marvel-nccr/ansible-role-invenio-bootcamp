[![Build Status](https://travis-ci.org/marvel-nccr/ansible-role-invenio-bootcamp.svg?branch=master)](https://travis-ci.org/marvel-nccr/ansible-role-invenio-bootcamp)

# Ansible Role: marvel-nccr.invenio_bootcamp

An ansible role that prepares the stage for installing invenio v3 for the invenio bootcamp 2019.

## Installation

```
pip install ansible
ansible-galaxy install marvel-nccr.invenio_bootcamp
```

## Role Variables

See `defaults/main.yml`

## Example Playbook

```yaml
- hosts: servers
  roles:
  - role: marvel-nccr.invenio_bootcamp
```

## Tests

This role uses [Molecule](https://molecule.readthedocs.io/en/latest/#) and
Docker for tests. Once Docker is installed, run tests using

```bash
pip install -r requirements.txt
molecule test
```

## License

MIT
