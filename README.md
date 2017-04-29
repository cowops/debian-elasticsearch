Debian-Elasticsearch
====================

Source Distributed Real Time Search & Analytics

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

elasticsearch_version: 1.0

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-elasticsearch, elasticsearch_version: 1.0 }

Tasks
-----

  - Install [elasticsearch](http://www.elasticsearch.org/)

License
-------

BSD
