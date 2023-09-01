Versions & Changelog
====================

Versions
--------

This data standard is versioned.

The scheme used is 3 numbers, `MAJOR.MINOR.PATCH` and follows `SemVer <https://semver.org/spec/v2.0.0.html>`_. In brief:

Increments to Patch numbers:

* should not change the intention of how the data standard actually works.
* may include modified and additional content to make clear things that were previously unclear.
* may include changes to correct previous mistakes.

Increments to Minor numbers:

* may include changes to the workings of the data standard, limited to additions of new models or fields in a backwards compatible manner.

Increments to Major numbers:

* may include changes to the workings of the data standard in a manner that is not backwards compatible. This will probably be modifications of existing models or fields.

Changelog
---------

Removed documents section from docs (this was stopping docs building)

1.1.0 - 2023-04-25
~~~~~~~~~~~~~~~~~~

Added policy sector to schema
Added headline evaluation to schema
Added other evaluation materials to schema
Removed documents from schema (replaced by headline and other evaluation materials).
Normally, this change would result in the version being bumped to v2. However, as there is currently no data entered on the system for the joining up dataset this is a special case and can be ignored. Hence v1.1.0

1.0.0 - 2023-02-22
~~~~~~~~~~~~~~~~~~

First release.
