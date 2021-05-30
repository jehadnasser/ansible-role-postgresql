postgresql
=========

[![Build Status](https://travis-ci.org/jehadnasser/ansible-role-postgresql.svg?branch=main)](https://travis-ci.org/github/jehadnasser/ansible-role-postgresql)


Install PostgreSQL on Ubuntu

Requirements
------------

Ubuntu

Role Variables
--------------

    db_user: __DB_USER__
    db_password: __DB_PASS__
    db_name: __DB_NAME__

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: jehadnasser.postgresql

License
-------

MIT

Author Information
------------------

https://github.com/jehadnasser

https://www.linkedin.com/in/jehadnasser
