[![Build Status](https://travis-ci.org/lifeofguenter/ansible-role-mssql.svg?branch=master)](https://travis-ci.org/lifeofguenter/ansible-role-mssql)

# Ansible Role for SQL Server (2017)

This ansible role will install SQL Server (2017) on Debian-like machines.

## Requirements

_None_

## Role Variables

```
mssql_sa_password: *required*
```

## Dependencies

_None_

## Example Playbook

```
- hosts: mssql
  roles:
    - { role: lifeofguenter.mssql }
```

## License

MIT

## Author Information

Gunter Grodotzki <gunter@grodotzki.co.za>
