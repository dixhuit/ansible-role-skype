# Ansible role: Skype

[![Build Status](https://travis-ci.org/danbohea/ansible-role-skype.svg?branch=master)](https://travis-ci.org/danbohea/ansible-role-skype)

Installs & configures Skype on Mac OS X.


## Requirements

- Mac OS 10.9+


## Role Variables

All role default variables are listed below along with their respective default values.

```
skype_DialpadOpen: 0
```

Sets default dialpad window visibility. Default is to hide the dialpad.

```
skype_ContactListViewMode: 1
```

Sets the default contacts view mode. Default is list view.


## Dependencies

- [danbohea.homebrew](https://galaxy.ansible.com/danbohea/homebrew)


## Example Playbook

```
- hosts: macbook
  connection: local

  roles:
    - role: ansible-role-skype
```

## License

MIT


## Author Information

This role was created by [Dan Bohea](http://bohea.co.uk) primarily for use with [Macsible](https://github.com/danbohea/macsible).
