mariadb Role
=========


Role Variables
--------------

```
mariadb_enable: true

database_bind_interface: '0.0.0.0'

database_name: dev
database_username: foo
database_password: foobar
```

----------------

```
#   requirements.yml
#
#   Example
# - src: https://github.com/ergontech-ansible-roles/mariadb
#   version: master
#   name: mariadb
```

License
-------

[MIT](LICENSE)