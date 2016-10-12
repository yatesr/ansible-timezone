Role Name
========

timezone

[![Build Status](https://travis-ci.org/yatesr/ansible-timezone.svg?branch=master)](https://travis-ci.org/yatesr/ansible-timezone)

Role Variables
--------------
```

# Default timezone.  Must be a valid tz database time zone.
timezone: UTC

```

Example Playbook
-------------------------
### playbook.yml

```

---
- hosts: all
  roles:
  - yatesr.timezone

  vars:
   timezone: America/New_York

```

License
-------

Apache 2.0

Author Information
------------------

Ryan Yates
