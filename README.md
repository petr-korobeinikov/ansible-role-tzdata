[![Build Status](https://travis-ci.org/pkorobeinikov/ansible-role-tzdata.svg?branch=master)](https://travis-ci.org/pkorobeinikov/ansible-role-tzdata)

ansible-role-tzdata
===================

Timezone configuration.

Requirements
------------

None.

Role Variables
--------------

* `tzdata_timezone` is a valid timezone name

Dependencies
------------

None.

Example Playbook
----------------

    ---
    - hosts: localhost
      become: true
      roles:
        - role: ansible-role-tzdata
          tzdata_timezone: America/Cancun


License
-------

BSD, MIT
