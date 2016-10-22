Role Name
=========

Installation of tools than any self-respecting JVM developer loves and needs.

Requirements
------------

TODO

Role Variables
--------------

* jvm_oracle_jdk_install: true
* jvm_oracle_jdk_version: jdk1.8.0_111
* jvm_oracle_jdk_path: 8u111-b14/jdk-8u111
* jvm_oracle_jdk_link_destination: oracle-jdk-8

* jvm_sdkman_install: true

* jvm_intellij_install: true
* jvm_intellij_version: 2016.2.4
* jvm_intellij_build: 162.2032.8

Dependencies
------------

No dependencies.

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.jvm-developer, jvm_sdkman_install: false, vm_intellij_version: 2016.2.4, jvm_intellij_build: 162.2032.8 }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
