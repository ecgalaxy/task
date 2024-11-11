ECGALAXY task role
==================

This Ansible role installs [Task](https://taskfile.dev/).

Task is a task runner / build tool that aims to be simpler and easier to use than, for example, GNU Make.

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

Upgrading
---------

In order to upgrade, reexecute this Ansible role after a new version has been released.

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

[ECGALAXY](https://code.europa.eu/groups/ecgalaxy/-/wikis/home) team.
