Changes
=======

In next release ...

Translation:

- Added Danish translation.

Bugfixes:

- The panel assignment class and traverser now inherit from
  ``OFS.Traversable.Traversable`` and implement the ``getId``
  method. This fixes an issue where a physical path would not be
  correctly computed.

1.0.2 (2012-04-19)
------------------

Bugfixes:

- Fixed issue where you could not add portlets to a panel other than
  the first (for a given manager). This fixes issue #3.

1.0.1 (2012-04-17)
------------------

Bugfixes:

- Fixed template formatting issue.

- Added markup from Plone's column renderer, wrapping each portlet in
  a structure that provides a unique portlet hash. Also, use a "safe"
  rendering method such that rendering may fail gracefully.

1.0 (2012-04-12)
----------------

- Initial public release.
