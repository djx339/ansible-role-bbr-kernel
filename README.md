Ansible Role: BBR Kernel
=========

Install newer kernel for supporting [bbr](https://github.com/google/bbr).

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  become: yes

  roles:
    - { role: djx339.bbr-kernel }
```

License
-------

BSD

Author Information
------------------

This role was created by [Daniel D](https://github.com/djx339).
