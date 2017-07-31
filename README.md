ansible-ntpdate
===============

[![Build Status](https://travis-ci.org/galexrt/ansible-ntpdate.svg?branch=master)](https://travis-ci.org/galexrt/ansible-ntpdate)

Ansible role for running ntpdate.

Install
-------

```
ansible-galaxy install galexrt.ansible-ntpdate
```

Requirements
------------

No special requirements.

Role Variables
--------------

```
# defaults file for ansible-ntpdate
ntpdate_enabled: true
# how many times ntpdate should be called
ntpdate_runs: 3
# the ntp server to use for ntpdate
ntpdate_server: "0.pool.ntp.org"
```

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

To use this role you add the following as the name of the role:
```
- hosts: servers
  roles:
    - { role: galexrt.ntpdate, ntpdate_run: true, ntpdate_runs: 5, ntpdate_server: "0.pool.ntp.org" }
```

License
-------

MIT

Author Information
------------------

If you have problems with the role, feel free to create an issue on Github or contact me by mail.
