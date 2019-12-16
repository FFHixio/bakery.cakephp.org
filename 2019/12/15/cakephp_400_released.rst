CakePHP 4.0.0 Released
======================

The CakePHP team is thrilled to announce the immediate availability of 4.0.0.
This is release begins a new chapter for CakePHP as 4.0 is now API stable and
the release windows for 2.x and 3.x begin.

Key Features
------------

* PHP 7.2 required.
* Streamlined APIs with all deprecated methods and behavior removed.
* Additional typehints across the framework giving you errors faster.
* Improved error messages across the framework.
* A refreshed application skeleton design.
* New database types for fixed length strings (CHAR), datetime with
  microseconds, and datetime with timezone types.
* ``Table`` now features ``OrFail`` methods that raise exceptions on failure
  making error handling more explicit and straightforward.
* Middleware for CSP headers, Form tampering prevention, and HTTPS enforcement.
* ``Cake\Routing\Asset`` to make generating asset URLs simple from anywhere in
  your application code.
* ``FormHelper`` now generates HTML5 validation errors.
* ``FormHelper`` now generates HTML5 datetime input elements.

Upgrading to 4.0
----------------

While 4.0 contains a number of
breaking changes we have prepared an exhaustive `migration guide
<https://book.cakephp.org/4/en/appendices/migration-guide.html>`__ covering all
the deprecated, removed, and new features.

Additionally, we have put together an `upgrade guide
<https://book.cakephp.org/4/en/appendices/4-0-upgrade-guide.html>`__ which gives
a step-by-step guide and CLI tool to help you upgrade your application. These
documents and companion tool will only improve as we collect more feedback from
people upgrading.

Contributors to 4.0.0
---------------------

CakePHP 4.0 would not have been possible without the hard work and contributions
from the following folks:


Thank you for all you've done to make CakePHP 4 a reality.

.. author:: markstory
.. categories:: release, news
.. tags:: release, news
