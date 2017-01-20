ansible-mysql
=========


Requirements
------------

# Environment

Azure China Centos-7.2 (Openlogic)

Role Variables
--------------

defaults/main.yml

	# MySQL package version is default to 9 (RedHat family)
	# then it will download from http://dev.mysql.com/get/mysql57-community-release-el7-9.noarch.rpm
	# the el7-9 indicates el{os_major_version}-{mysql_package_version}, and the os_major_version 
	# will be auto detected
	mysql_package_version: 9


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: mysql
      roles:
         - { role: ansible-mysql }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
