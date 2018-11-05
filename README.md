# Update-Reboot
This playbook works for on CentOS, Fedora, Ubuntu, Debian and Suse.

This playbook will update package database and reboot the hosts.

*NOTE This playbook reboots hosts, any running service on the hosts will be interrupted by this reboot.

Steps:

Updates yum package index
Refresh the cache
Reboots host
Wait for the system to boot up
