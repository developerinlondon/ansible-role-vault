Vault
=========

Install Hashicorp Vault on a Debian/Ubuntu, EL, or macOS system.

Requirements
------------

None

Role Variables
--------------

vault_version: "0.7.3" [default]

Dependencies
------------

None

Example Playbook
----------------

An example of how to use this role:

    - hosts: servers
      roles:
         - { role: bkyoung.vault, vault_version: "0.7.3" }

License
-------

BSD

Author Information
------------------

Brandon Young <bkyoung@gmail.com>
