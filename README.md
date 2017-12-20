# docker-login-ansible-role

Ansible role to perform docker logins.

Role Variables
--------------

```
docker_registries: []
```

Registries  Examples
----------
```
docker_registries:
  # docker hub
  - url: index.docker.io
    username: XXX
    password: ZZZ
  # if you have the ca certificate
  - url: my.custom.registry
    username: XXX
    password: ZZZ
```
License
-------

Apache License 2
