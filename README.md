## virtualbox

[![CI](https://github.com/Oefenweb/ansible-virtualbox/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-virtualbox/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-virtualbox-blue.svg)](https://galaxy.ansible.com/Oefenweb/virtualbox/)

Set up [VirtualBox](https://www.virtualbox.org/) in Debian-like systems.

#### Requirements

* `software-properties-common` (will be installed)
* `dirmngr` (will be installed)

#### Variables

* `virtualbox_version` [default: `6.1`]: Version to install
* `virtualbox_install`: [default: `[]`]: Additional packages to install (e.g. `dkms`)

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - virtualbox
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-virtualbox/issues)!
