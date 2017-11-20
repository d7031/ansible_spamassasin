Role Name
=========

manage spamassasin rules

Requirements
------------

none

Role Variables
--------------

none

Dependencies
------------

none

Example Playbook
----------------

- name: update spamassassin private rules
  hosts: mailserver
  become: true
  roles:
    - manage-spamassassin

License
-------

GPLv3 or later

Author Information
------------------

Tom Geissler
Tom@d7031.de
