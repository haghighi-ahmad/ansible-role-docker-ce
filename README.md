Ansible Role: Install Docker CE
=========

[![Build Status][travis-build-status]][travis-tests] [![Ansible Role][ansible-role-shield]][ansible-role]

This role install Docker CE 

Requirements
------------

### Ansible Modules

* package
* apt_key
* apt_repository

Role Variables
--------------

Example Playbook
----------------

    - hosts: docker
      roles:
         - { role: docker-ce }

License
-------

AGPLv3

Author Information
------------------

Ahmad Haghighi. (https://ahmadhaghighi.com)


[travis-build-status]: https://api.travis-ci.org/haghighi-ahmad/ansible-role-docker-ce.svg?branch=master&style=flat-square "Travis-CI Build Status"
[travis-tests]: https://travis-ci.org/haghighi-ahmad/ansible-role-docker-ce "Travis-CI Tests"
[ansible-role-shield]: https://img.shields.io/ansible/role/46811.svg?style=flat-square "Docker CE on Ansible Galaxy"
[ansible-role]: https://galaxy.ansible.com/haghighi_ahmad/docker_ce "Docker CE on Ansible Galaxy"
