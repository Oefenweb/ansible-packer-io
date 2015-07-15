## packer-io

[![Build Status](https://travis-ci.org/Oefenweb/ansible-packer-io.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-packer-io) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-packer--io-blue.svg)](https://galaxy.ansible.com/list#/roles/4394)

Set up [Packer](https://packer.io/) by HashiCorp in Debian-like systems.

#### Requirements

* `unzip` (will be installed)

#### Variables

* `packer_io_version` [default: `0.8.1`]: Version to install
* `packer_io_install_prefix` [default: `/opt`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - packer-io
```

#### License

MIT

#### Author Information

Mischa ter Smitten (based on work of [Florian Pelgrim](https://github.com/craneworks))

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-packer-io/issues)!
