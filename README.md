System - dhparam
================

This role generates a dhparam file with the choosen length

Requirements
------------

None

Role Variables
--------------

This variable will set the legth of `dhparams.pem`:

	shokinn_dhparam_size: "4096"

Dependencies
------------

None

Example Playbook
----------------

	---
	- hosts: servers
	  roles:
	     - { role: shokinn.system.dhparam, shokinn_dhparam_size: "4096" }

License
-------

MIT

Author Information
------------------

This role was originally created in 2019 by [Philip Henning](https://pphg.tech).
