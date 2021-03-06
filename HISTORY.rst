.. :changelog:

History
=======

Version 2.2.1 (2020-05-26)
--------------------------

* Fix choices for internal statuses

Version 2.2.0 (2020-05-03)
--------------------------

* Add template tag
* Add helper for REST integration

Version 2.1.0 (2020-04-30)
--------------------------

* Definitions for all internal data types and statuses
* Full type hinting
* Fixed bugs (thanks to `Kacper Pikulski <https://github.com/pikulak>`_!)


Version 2.0.0 (2020-04-18)
--------------------------

* BREAKING: Complete redesign of internal APIs.
* Supports only Django 2.2+ and Python 3.6+
* Payment and Order became swappable models - like Django's User model
* Payment acts as customizable interface to PaymentProcessor instances (but be careful).
* Payment statuses guarded with django-fsm
* Broker plugins separated from main repo - easier updates.


See :doc:`prehistory <HISTORY_OLD>`
