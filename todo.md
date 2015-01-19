* Features:
 * involve local user (all `rdiff-backup` commands must be run as local user),
 * Error handling:
  * e-mail notifications,
  * error types: `rdiff-backup` not installed, connection failed, SSH access denied, `pre_backup_cmd` failed, etc.
 * log rotation (destination cannot be entirely configurable),
 * installer
* Test:
 * use case: `rdbmange -m N` on cron,
 * use case: `rdbmanage -j JOB`,
* Documentation:
 * configuration file,
 * UI,
 * internals,
 * error handling,
 * return codes,
