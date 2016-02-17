Ansible role for bash history
=========

Automatically configure bash history following best guidelines to make it more usable in a production environnement

Requirements
------------



Role Variables
--------------

- histsize : Max lines in history
	* Type : integer
	* Default : 10000

- histfilesize : Max size of file used to store history
	* Type : integer
	* Default : 20000

- histtimeformat : Format used to format time
	* Type : string
	* Default : "%F %T "


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

	- hosts: all
	  roles:
	    - {role: ansible-history }

License
-------

BSD

Author Information
------------------

pauchet.valentin at gmail.com
