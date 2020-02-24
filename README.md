Ansible Role: Install Docker CE
=========

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
