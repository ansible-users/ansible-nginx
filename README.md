
[![Ansible Role](https://img.shields.io/badge/role-cupen.nginx-brightgreen.svg)](https://galaxy.ansible.com/ansible-users/nginx/)

Nginx
=========

Install [nginx] from official release.

Requirements
------------

* `ansible`

Role Variables
--------------

* `version` :  version of nginx.



Dependencies
------------



Example Playbook
----------------

Install nginx from yum repo.

```yaml
- hosts: servers
  roles:
     - { role: cupen.nginx, version: "1.12.0", worker_processes: 8, nginx_max_clients: 2048 }

```

License
-------

WTFPL

```
DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
           Version 2, December 2004

Copyright (C) 2017 cupen <cupen@foxmail.com>

Everyone is permitted to copy and distribute verbatim or modified
copies of this license document, and changing it is allowed as long
as the name is changed.

   DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

0. You just DO WHAT THE FUCK YOU WANT TO.
```

Author Information
------------------

智慧与美貌的并重，英雄与侠义的化身！

<cupen@foxmail.com>

[nginx]: http://nginx.org/packages/centos/
