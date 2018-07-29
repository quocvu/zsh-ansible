[![Build Status](https://img.shields.io/travis/quocvu/zsh-ansible.svg)](https://travis-ci.org/quocvu/zsh-ansible)
[![Ansible Role](https://img.shields.io/ansible/role/27916.svg)](https://galaxy.ansible.com/quocvu/zsh)

zsh
=========

Install and configure ZSH shell and Oh-my-zsh along with the powerline9k theme.

Requirements
------------

On OSX, homebrew must be already installed.

Role Variables
--------------


Dependencies
------------

none

Example Playbook
----------------

To install ZSH, add the following in your playbook:

```
- hosts: servers
  roles:
    - { role: quocvu.zsh }
```

License
-------

MIT

Author Information
------------------

Quoc Vu  
https://github.com/quocvu  
https://linkedin.com/in/quocvu  
