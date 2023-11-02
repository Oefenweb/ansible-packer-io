## packer-io

[![CI](https://github.com/Oefenweb/ansible-packer-io/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-packer-io/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-packer--io-blue.svg)](https://galaxy.ansible.com/Oefenweb/packer_io)

Set up [Packer](https://packer.io/) by HashiCorp in Debian-like systems.

#### Requirements

* `unzip` (will be installed)

#### Variables

* `packer_io_version` [default: `1.9.1`]: Version to install
* `packer_io_install_prefix` [default: `/opt`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.packer-io
```

#### License

MIT

#### Author Information

Mischa ter Smitten (based on work of [Florian Pelgrim](https://github.com/craneworks))

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-packer-io/issues)!
