zabbix_frontend Role
=========

Install and configure the zabbix web frontend.

[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-neoloc.zabbix_frontend-blue.svg)](https://galaxy.ansible.com/neoloc/ansible-role-TEMPLATE/)


Requirements
------------

None

Role Variables
--------------

```yaml
zabbix_frontend_configure: true
zabbix_frontend_mysql_connection: socket
zabbix_frontend_database_name: zabbix
zabbix_frontend_database_user: zabbix
zabbix_frontend_database_pass: zabbix
zabbix_frontend_database_host: localhost
zabbix_frontend_database_port: 3306
zabbix_frontend_server_name: zabbix
```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
         - neoloc.zabbix_frontend

License
-------

See license.md

Author Information
------------------

[![Github](https://img.shields.io/badge/Github-neoloc-blue.svg)](https://github.com/neoloc)
