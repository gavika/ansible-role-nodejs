Role Name
=========

Install NodeJS

Requirements
------------

None

Role Variables
--------------
```
nodejs_install_using_nodesource: false
nodejs_version: "16.x"
nodejs_install_npm_separately: false
```

Dependencies
------------

None

Example Playbook
----------------
```
- hosts: nodejs_servers
  remote_user: vagrant
  vars:
    nodejs_install_using_nodesource: true
    nodejs_version: "12.x"
  roles:
    - gavika.ansible_role_nodejs
```

License
-------

Apache 2

Author Information
------------------
Sudheer Satyanarayana.
Gavika Information Technologies Pvt. Ltd. https://www.gavika.com/
