# The Homelab

My homelab is just a single server. Hardly a lab, you'd say,
but I beg to differ!

At the moment, the primary goal is to compile a config to deploy the
entire infrastructure for a small business.

Right now, I'm finishing the first phase: deploying the lab infrastructure.
I've manually installed and configured the server and services, essentially
creating my own private cloud. Yet, it should be just as easy to deploy on
actual cloud services like EC2 or DigitalOcean.

The second phase will consist of configuring and deploying the base services, in
Puppet code and Hiera data:
* Foreman
* Foreman Smart Proxies
* Puppetmaster
* Libvirt
* DNS (bind9)
* DHCP (isc-dhcp-server)
* TFTP (tftpd-hpa)
* Backups (backuppc)
* Mail server (postfix + dovecot)
* File server (samba/nfs)
* Database (mysql)
* Git server (git-gui/gitolite/gitlab)
* Monitoring (zabbix/icinga2)

By the way, I've picked Ubuntu 14.04.3 as primary OS.

A few other goals and/or usecases include:
* learn Puppet
* write my own knowledgebase
* KISS
* Share it!
