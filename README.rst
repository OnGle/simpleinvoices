SimpleInvoices - Invoicing system
=================================

`SimpleInvoices`_ is a web based invoicing system developed by the
community for the community that helps users create quick and nice
looking invoices without having to set up to much. Install the software,
enter a biller, a customer and go nuts creating invoices!

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- SimpleInvoices configurations:
   
   - Installed from upstream source code (via git) to /var/www/simpleinvoices

     **Security note**: Updates to SimpleInvoices may require supervision so
     they **ARE NOT** configured to install automatically.

- SSL support out of the box.
- `Adminer`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL: username **root**
-  Adminer: username **adminer**
-  SimpleInvoices: username is email set on first boot


.. _SimpleInvoices: http://www.simpleinvoices.org/
.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _Adminer: http://www.adminer.org/
