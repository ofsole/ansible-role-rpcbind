ansible-role-rpcbind
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

Here is a list of all the default variables for this role, which are also available in `defaults/main.yml`.
```
package_state: 'present'
service_state: 'started'
service_enabled: 'yes'
```

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         -  role: rpcbind

License
-------

BSD

Author Information
------------------

Elvis Cai
