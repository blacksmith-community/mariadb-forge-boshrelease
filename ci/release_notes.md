# Bug Fixes

- Removed the "application user" that was introduced in the last
  release, since it caused too many problems with existing
  applications that expected root access to the databaser server
  instance.  Now, the admin account has access to the pre-created
  database, and those credentials are used.

# Improvements

- MariaDB upgraded from 10.1.20 to 10.1.41

