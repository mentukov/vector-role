Vector-role
=========

Эта роль производит установку Vector

Role Variables
--------------
| Variable  |      |
|:-----|:----|
| vector_version | Версия ПО Vector для установки |

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: vector }

License
-------

MIT

Author Information
------------------

Alexey Mentukov
