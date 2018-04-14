[![Ansible Role](https://img.shields.io/ansible/role/25031.svg)][galaxy]
[![Ansible Role](https://img.shields.io/ansible/role/d/25031.svg)][galaxy]


# Introdution
Install [nginx] from official release.

# Requirements
* `ansible` >= 2.0

# Role Variables
* `version` :  version of nginx.
* `nginx_http_params`: a dict of http params.


# Dependencies
empty.


# Example Playbook
```yaml
- hosts: servers
  var:
    nginx_http_params:
      gzip: "on"
  roles:
     - { role: cupen.nginx, version: "1.12.2", worker_processes: 8, nginx_max_clients: 2048 }

```

# License

WTFPL

```
DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
           Version 2, December 2004

Copyright (C) 2018 cupen <xcupen@gmail.com>

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

[nginx]: http://nginx.org/packages/centos/
[galaxy]: https://galaxy.ansible.com/ansible-users/nginx/
