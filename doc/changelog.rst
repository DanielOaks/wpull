==========
What's New
==========

0.XX (2014-MM-DD)
=================

* Database change: SQLAlchemy is now used for the URL Table.

  * Scripts: ``url_info['inline']`` now returns a boolean, not an integer.


0.13 (2014-01-31)
=================

* Supports reading HTTP responses with gzip content type.


0.12 (2014-01-31)
=================

* No changes to program usage itself.
* More documentation.
* Major API changes due to refactoring:

  * ``http.Body`` moved to ``conversation.Body``
  * ``document.HTTPScraper``, ``document.CSSScraper`` moved to ``scraper`` module.
  * ``conversation`` module now contains base classes for protocol elements.
  * ``processor.WebProcessorSession`` now uses keyword arguments
  * ``engine.Engine`` requires ``Statistics`` argument.


0.11 (2014-01-29)
=================

* Implements ``--progress`` which includes a progress bar indicator.
* Bumps up the HTTP connection buffer size to support fast connections.


0.10.9 (2014-01-28)
===================

* Adds documentation. No program changes.


0.10.8 (2014-01-26)
===================

* Improves robustness against bad HTTP protocol messages.
* Fixes various URL and IRI handling issues.
* Fixes ``--input-file`` to work as expected.
* Fixes command line arguments not working under Python 2.


0.10 (2014-01-23)
=================

* Improves handling on URLs and document encodings.
* Implements ``--ascii-print``.
* Fixes Lua scripting conversion of Python to Lua object types.


0.9 (2014-01-21)
================

* Adds basic SSL options.


0.8 (2014-01-21)
================

* Supports Python and Lua scripting via ``--python-script`` and
  ``--lua-script``.


0.7 (2014-01-18)
================

* Fixes robots.txt support.


0.6 (2014-01-17)
================

* Implements ``--warc-append``, ``--concurrent``.
* ``--read-timeout`` default is 900 seconds.


0.5 (2014-01-17)
================

* Implements ``--no-http-keepalive``, ``--rotate-dns``.
* Adds basic support for HTTPS.


0.4 (2014-01-15)
================

* Implements ``--continue``, ``--no-clobber``, ``--timestamping``.


0.3.2 (2014-01-07)
==================

* Fixes database rows not saved correctly.


0.3 (2014-01-07)
================

* Implements ``--hostnames`` and ``--exclude-hostnames``.


0.2 (2014-01-06)
================

* Implements ``--header`` option.
* Various 3to2 bug fixes.


0.1 (2014-01-05)
================

* The first usable release.


