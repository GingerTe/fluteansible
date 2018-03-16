Flute
=========

Installation of Course Orchestra Flute (https://corchestra.ru/wiki/index.php?title=Flute)

Requirements
------------

Java 8 (Oracle)

Role Variables
--------------

* flute_build: flute build number
* flute_group: the group for flute service user (default valute is flute)
* flute_dir: where to intall flute (default value is /opt/flute)


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
         oracle_java_version: 8
         oracle_java_version_update: 131
      roles:
         - role: ansiblebit.oracle-java
         - role: flute

License
-------

MIT

Author Information
------------------

https://corchestra.ru/en