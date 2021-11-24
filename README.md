# Ansible Role for SQL Server (2017)

[![Build Status](https://travis-ci.com/lifeofguenter/ansible-role-mssql.svg?branch=main)](https://travis-ci.com/lifeofguenter/ansible-role-mssql)

This ansible role will install SQL Server (2017 & 2019) on Debian-like systems.

## Requirements

_None_

## Role Variables

```
mssql_sa_password: *required*
```

```
mssql_memory_memorylimitmb: "{{ (ansible_memtotal_mb * 0.8) | round | int }}"
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

Günter Grodotzki <gunter@grodotzki.com>
