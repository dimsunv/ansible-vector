Role Name
=========

Simple vector role.

Role Variables
--------------
F: You can specify a particular version (or * for the latest). Please note that downgrade isn't supported.

`vector_version: "0.23.3"`

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Install vector
      hosts: server
      vars:
        - vector_version: "0.23.3"
      roles:
        - ansible-vector

License
-------

BSD

Author Information
------------------

Role by Dimsunv.

Dear contributors, thank you.