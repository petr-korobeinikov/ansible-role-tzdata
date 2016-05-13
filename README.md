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
