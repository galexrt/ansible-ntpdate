ansible-ntpdate
===============

[![Build Status](https://travis-ci.org/galexrt/ansible-ntpdate.svg?branch=master)](https://travis-ci.org/galexrt/ansible-ntpdate)

Ansible role for running ntpdate.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

To use this role you add the following as the name of the role:
```
- hosts: servers
  roles:
    - { role: galexrt.ntpdate, ntpdate_run: true, ntpdate_runs: 5 }
```

License
-------

MIT

Author Information
------------------

If you have problems with the role, feel free to create an issue on Github or contact me by mail.
