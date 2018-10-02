# PostgreSQL 9.6

Install PostgreSQL 9.6 and create user, setup development and test database.

install only command-line tools:
```yaml
- hosts: localhost
  connection: local
  vars:
    - postgresql_tools_only: yes
```
