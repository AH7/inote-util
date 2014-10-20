# inote-util Release Notes

This file summarizes the changes bundled in each release of `inote-util`.

<!-- toc -->

## Release 0.3.2 - 20 October 2014

### Enhancements

 * Added `Util.blank_to_null`.

 * Added option to `Util.handle_error` for throwing an error rather than inovking a callback.

## Release 0.3.1 - 18 October 2014

### Bug Fixes

 * Fixed issue with `Util.is_blank()` not testing for non-alphanumeric characters like `/` or `$`.

### Enhancements

 * Added `Util.hash_password`, `Util.validate_hash_password` and `Util.slow_equals` methods.

## Release 0.2.1 - 15 October 2014

### Enhancements

 * Added `Config` (`config.coffee`).

## Release 0.2.0 - 5 October 2014

### Bug Fixes

 * Various documentation and test updates.

### Enhancements

 * Added `timer.lap()` to `Stopwatch`.

 * Added `Util.escape_for_regexp`.

 * Added "marker" parameter to `Util.truncate`, and tweaked related logic.

## Release 0.1.1 - 30 September 2014

 * *Change log not tracked up to and including this release.*