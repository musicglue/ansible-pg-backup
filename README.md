PG Backup
=========

Role Variables
--------------

```
---
backup_config_dir: /etc/pg_backup
backup_hostname: localhost
backup_pg_user: "{{ backup_user }}"
backup_user: postgres
backup_tmp_dir: /tmp/pg_backup
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: musicglue.pg_backup, backup_hostname: '127.0.0.1' }

License
-------

MIT

