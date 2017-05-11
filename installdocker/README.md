Role Name
=========

Automatically installs latest Docker from APT, and Docker Compose from GitHub.

Requirements
------------

* APT-based distribution. (tested on Debian)
* Internet connection
* grep, cut

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - installdocker

License
-------

GPLv3

Author Information
------------------

Yekta Leblebici <yekta@iamyekta.com>
http://iamyekta.com
