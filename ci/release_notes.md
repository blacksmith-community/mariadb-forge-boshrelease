# Improvements

- Create a default DB and add uri and jdbcUrl strings to the VCAP provided to the app.

# Bug Fixes

- The fix for standalone AZ specification, shipped in the previous
  release, was only a half-fix.  This release has the full story,
  and the standalone AZ is propagated properly to the service
  definitions now.  Thanks @elric392!
