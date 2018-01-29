Install vim [![Build Status](https://travis-ci.org/shengyou/ansible-role-vim.svg?branch=master)](https://travis-ci.org/shengyou/ansible-role-vim)
=========

install vim.

* Ubuntu 14.04
* CentOS 6

Requirements
------------

* ansible >= 2.4
* python >= 2.6

Dependencies
------------

none.

Example Playbook
----------------

```
- name: install_vim.yml
  hosts: myhost
  gather_facts: yes
  become: yes

  roles:
    - install_vim

```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
