Role Name
=========

Install vector

Requirements
------------

Rocky linux

Role Variables
--------------
vector_version: "0.33.1"
install_dir: "/opt/vector"

Dependencies
------------

Cickhouse
Vector
Lighthouse

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: server
      roles:
        - role: vector-role   
