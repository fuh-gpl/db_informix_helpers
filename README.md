db_informix_helpers
===================

Misc scripts to make life with informix databases easier

ifxini.EXAMPLE:
 Systemwide configfile for database parameters. Install to
 /usr/local/etc/ifxini.

runlevel-scripts:
 rc.informix.rhel: redhat and alikes
 rc.informix.sles: suse linux enterprise server

helpers:
 Scripts primarily for use via cron. Install
 to /usr/local/bin and /usr/local/sbin. The 
 Scripts can be called via the root-crontab, they
 usually only output anything in case of a warning or
 an error. With a working MTA the cronjobs then send mail
 only in case of en error.

 
