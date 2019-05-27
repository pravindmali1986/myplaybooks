Cluster elasticsearch
=====================
An ansible role to install and configure elasticsearch cluster in centos 7.
3 master nodes + 6 data nodes

Requirements
------------
- Centos 7
- Java 1.8

Role Variables
--------------
- ansible/roles/elasticsearch-node/defaults/main.yml

Dependencies
------------
none

Example Playbook
----------------
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: elastic-servers
      roles:
        - elasticsearch-node

License
-------
BY-NC-SA

Author Information
------------------
Pragsis Bidoop
