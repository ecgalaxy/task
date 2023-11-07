ECGALAXY task role
==================

Installs Task - https://taskfile.dev/

Requirements
------------

* The `tar` and `wget` commands, which can be provided by `ecgalaxy.common_packages`.

Role Variables
--------------

See defaults.

Dependencies
------------

* optional: ecgalaxy.common_packages

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.bootstrap
        - ecgalaxy.common_packages
        - ecgalaxy.task

One-liner
---------

    bash <(curl -s https://code.europa.eu/-/snippets/1/raw/main/ansible-role.sh) ecgalaxy.task

See [ansible-role](https://code.europa.eu/-/snippets/1) for instructions.

Please verify the script integrity first.

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
