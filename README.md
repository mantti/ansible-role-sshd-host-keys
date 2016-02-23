ansible-role-sshd-host-keys
=========

Installs pre-generated sshd host keys.

Requirements
------------

 - A set of pre-generated sshd host keys.
  - See https://github.com/CSC-IT-Center-for-Science/ansible-role-pxe_config
 - This should only be run on a compute node with ansible-pull

Role Variables
--------------

See defaults/main.yml

Dependencies
------------

https://github.com/CSC-IT-Center-for-Science/ansible-role-pxe_config

and an sshd role which configures sshd to use the new known_hosts files

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-sshd-host-keys }

License
-------

MIT

Author Information
------------------

https://github.com/martbhell
https://github.com/jabl

