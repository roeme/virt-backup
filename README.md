virt-backup
===========

libvirt-based domain backup tool.

DESCRIPTION
-----------
virt-backup backs up domains. In contrast to existing tools, this will

 * Not require you to run LVM or anything likewise on the host
 * Not require the domain's storage to be of any particular format
 * Backup the domain's filesystems in a true consistent state, using freeze/thaw
 * Handle snapshotting transparently
 * Backup running domains
 * Use syslog


BUGS
----
While sounding good; this is still under construction.
