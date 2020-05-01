Hardening Focal Fossa
=========

![master](https://github.com/jake-morgan/ansible-role-hardening-focal/workflows/master/badge.svg)
[![galaxy](https://img.shields.io/badge/galaxy-jake__morgan.hardening__focal-5bbdbf.svg)](https://galaxy.ansible.com/jake_morgan/hardening_focal)

Harden Ubuntu 20.04 LTS (Focal Fossa) to guidelines laid out in:

* [Linode Secure Your Server](https://www.linode.com/docs/security/securing-your-server/)
* [Rackspace Linux Security Best Practices](https://support.rackspace.com/how-to/linux-server-security-best-practices/)

Requirements
------------

Tested only on Ubuntu 20.04 LTS Focal Fossa. No guarantee it will work on other distros or Ubuntu versions.

Role Variables
--------------

| Variable | Description | Type| Required | Default |
|-|-|-|-|-|
| `var_name` | Description... | Bool/String/Number | Yes/No | `value` |

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: jake-morgan.hardening-focal
```

License
-------

MIT
