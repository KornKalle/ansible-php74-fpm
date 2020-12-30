Role Name
=========

This role installs php 7.4 and php-fpm under Debian 10 / Ubuntu 18.04, 20.04 and RHEL / CentOS 8.
Default is listening on 127.0.0.1:9000 for fpm service, but this can be overridden.
Resource limits will be quite high, but can be tuned with overriding the variables found in defaults/main.yml.

Requirements
------------

Ansible >= 2.9

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: nginx
      roles:
         - { role: kornkalle.php74_fpm }

License
-------

GPLv3

Author Information
------------------

n.berg@backslashseven.de
