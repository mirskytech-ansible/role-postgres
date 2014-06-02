Description
----------------------

Installs postgres 9.3 and creates databases/users based on variables. Also installs
``pg_dump`` and ``pg_load`` for use in backup/restore of databases.

Variables
----------------------

If you'd like this role to also create database with owners::

  databases:
    - { user: ownerA, database: databaseA }
    - { user: ownerB, database: databaseB }

    
References
----------------------

- https://wiki.postgresql.org/wiki/Apt
