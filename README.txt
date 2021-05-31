ARCHIVED
========

This project is no longer maintained.  If someone would like to adopt it I'll be happy to transfer it.

---

This package contains tools designed to work with the Graphite data
collection system.  See http://graphite.wikidot.com/ for details.

This package consists of 3 categories:

* init -- a System V style init script to maintain the graphite carbon
     processes
* xymon -- a Xymon task to set column status based on data retrieved
      from Graphite.
* probes -- a set of system probes to feed data to graphite
    - graphite-exim: Scrape EXIM logs for interesting information about mail
    - graphite-log: process generic logs (yes, there are many implementations of this kind of thing)
    - graphite-ping: run ping and report interesting stats on the result (ping time, packet loss and functions thereof)
    - graphite-probe-disk-latency: probe only disk latency from graphite-probe-linux
    - graphite-probe-linksys-cable: probe power and connection data from Linksys cable modems (scrapes the web page)
    - graphite-probe-linux: probe various interesting Linux system characteristics (NOTE:  I've stopped using this in favor of Host sFlow)
    - graphite-probe-nfs-client: NFS client statistics
    - graphite-probe-nfs-server: NFS server statistics
    - graphite-probe-sensors: Linux "sensors" package
    - graphite-probe-smartmon: collect data from smartmon about drive temps, failing sectors, etc
    - graphite-probe-vmware-server: interesting information from VMWare server (GSX -- now end of lifed)
    - graphite-run-probes: a wrapper for running other probes
    - graphite-samba-logs: collect result information from SAMBA logs

These have can be used indepdently.

See the project page http://deweysasser.com/software/graphiteutils for
more details.

Thanks,

--
Dewey Sasser
<dewey@deweysasser.com>

