az
=========

Installs the latest version of the Azure CLI onto Ubuntu.

Reference: https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-apt?view=azure-cli-latest

Requirements
------------

All pre-reqs are installed by the role.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: ubuntu
  remote_user: overlord
  become: true
  roles:
     - { role: az }

License
-------

BSD

Author Information
------------------

Richard Cheney, Microsoft. Email: richard.cheney@microsoft.com 
