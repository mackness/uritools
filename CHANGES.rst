0.8.0 UNRELEASED
----------------

- Refactor ``uriencode()`` and ``uridecode()``.


0.7.0 2014-10-12
----------------

- Add optional port parameter to ``SplitResult.getaddrinfo()``.

- Cache ``SplitResult.authority`` subcomponents.


0.6.0 2014-09-17
----------------

- Add basic IPv6 support.

- Change ``SplitResult.port`` back to string, to distinguish between
  empty and absent port components.

- Remove ``querysep`` and ``sep`` parameters.

- Do not raise ``ValueError`` if scheme is not well-formed.

- Improve Python 3 support.


0.5.2 2014-08-06
----------------

- Fix empty port handling.


0.5.1 2014-06-22
----------------

- Add basic Python 3 support.


0.5.0 2014-06-21
----------------

- Add ``SplitResult.getaddrinfo()``.

- Support query mappings and sequences in ``uricompose()``.


0.4.0 2014-03-20
----------------

- Fix ``SplitResult.port`` to return int (matching urlparse).

- Add ``SplitResult.getquerylist(), SplitResult.getquerydict()``.


0.3.0 2014-03-02
----------------

- Add result object accessor methods.

- Update documentation.


0.2.1 2014-02-24
----------------

- Fix IndexError in ``urinormpath()``.

- Integrate Python 2.7.6 ``urlparse`` unit tests.


0.2.0 2014-02-18
----------------

- Add authority subcomponent attributes.

- Return ``DefragResult`` from ``uridefrag()``.

- Improve edge case behavior.


0.1.0 2014-02-14
----------------

- Initial beta release.