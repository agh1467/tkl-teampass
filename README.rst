TeamPass - A Collaborative Passwords Manager
======================

`TeamPass`_ is a Passwords Manager dedicated for managing passwords in
a collaborative way on any server Apache, MySQL and PHP. It is
especially designed to provide passwords access security for allowed
people. This makes TeamPass really useful in a Business/Enterprise
environment and will provide to IT or Team Manager a powerful and
easy tool for customizing passwords access depending on the user's role. 

This appliance includes all the standard features in `TurnKey Core`_,
`TurnKey LAMP`_, and on top of that:

- Teampass configurations:
   
   - Installed from upstream source code to /var/www/teampass

- SSL support out of the box.
- `PHPMyAdmin`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Webmin modules for configuring Apache2, PHP, MySQL.

Credentials *(passwords set at first boot)*
-------------------------------------------

- Webmin, SSH, MySQL, phpMyAdmin: username **root**
- TeamPass: username **admin**


.. _TeamPass: http://teampass.net/
.. _TurnKey Core: http://www.turnkeylinux.org/core
.. _PHPMyAdmin: http://www.phpmyadmin.net
