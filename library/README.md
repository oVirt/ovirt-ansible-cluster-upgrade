New modules
===========

Here is the list of newly added modules by this role:

1. ovirt_api_facts.py

- Contains a new module to retrieve facts from oVirt api: [PR](https://github.com/ansible/ansible/pull/28875).
  The module will be available in Ansible 2.5.

Updated modules
===============

Here is list of updated modules:

1. ovirt_auth.py

- Support the ENV variables for `ovirt_auth`: [PR](https://github.com/ansible/ansible/pull/34878)
  The module will be available in Ansible 2.5.

2. ovirt_hosts.py

- Support `reboot_after_upgrade` parameter in `ovirt_hosts`: [PR](https://github.com/ansible/ansible/pull/35956)
  The fix will be available in Ansible 2.6.
