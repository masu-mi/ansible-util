masu_mi.util
=========

This role contains util tasks in order to be used by `include_role`.

Requirements
------------

I think `include_role` usable are premise.
So ansible  required v2.2 or later.

Role Variables
--------------

**none**

Dependencies
------------

**none**

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
  - name: reboot for activating SELinux new configuration
    include_role:
      name: util
      task_from: reboot
      private: true
```

License
-------

BSD

Author Information
------------------

[Masumi KANAI](masumi.net@gmail.com)
