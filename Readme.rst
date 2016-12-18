Opencart - An Opensource Shopping Cart System
========================================

Opencart - An Opensource Shopping Cart System

This appliance includes all the standard features in `TurnKey Core`_, and on top of that:

- Opencart 
  
   - Installed from release upstream source to /var/www/opencart
   - Composer globally installed for all your projects
   - Support for Automatic Google Optimized Images via systemctl (disabled by default "systemctl start opencart-image-compress")

- SSL support out of the box.
- `Adminer`_ administration frontend for MySQL (listening on port 12322 - uses SSL).
-  Postfix MTA (bound to localhost) to allow sending of email (e. g. password recovery).
-  Webmin modules for configuring Apache2, PHP, MySQL and Postfix.


Opencart Documentation: http://Opencart.com

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL, Adminer: username **root**


.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _Adminer: http://www.adminer.org
