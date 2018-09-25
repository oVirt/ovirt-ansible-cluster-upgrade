Updated modules
===============

Here is list of updated modules:

1. ovirt_hosts.py

- Support `reboot_after_upgrade` parameter in `ovirt_hosts`: [PR](https://github.com/ansible/ansible/pull/35956)
  The fix will be available in Ansible 2.6.

- Check if migration failed during upgrade: [PR](https://github.com/ansible/ansible/pull/46104)
  The fix will be available in Ansible 2.8.

2. ovirt_auth.py

- In case of token is passed username/pass is not required: [PR](https://github.com/ansible/ansible/pull/42738)
  The fix will be available in Ansible 2.6.1.
