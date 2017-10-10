Flute
=========

Installation of Course Orchestra Flute (https://corchestra.ru/wiki/index.php?title=Flute)

Requirements
------------

Java 8 (Oracle)

Role Variables
--------------

* flute_url: url to flute.jar
* flute_lib_url: url to archive with libraries needed for flute
* flute_version: version of flute 



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

GPLv3

Author Information
------------------

https://corchestra.ru