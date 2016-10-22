Role Name
=========

Installation of tools than any self-respecting software developer loves and needs.

Requirements
------------

TODO

Role Variables
--------------

TODO

Dependencies
------------

No dependencies.

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.software-developer, jvm_sdkman_install: false, vm_intellij_version: 2016.2.4, jvm_intellij_build: 162.2032.8 }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
