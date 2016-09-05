zabbix-bacula
===
Bacula backups monitoring for Zabbix (Only Bacula-PGSQL)

resources/items/triggers
===
* Auto Discovery JOBS (lld discovery)
* JOB status (item)
* JOB elapsed time (item/graph) by FULL/INCREMENTAL/DIFFERENTIAL 
* JOB size (item/graph) by FULL/INCREMENTAL/DIFFERENTIAL
* Backup doesnt OK (trigger)
* Backup doesnt executed at last 24 hours (trigger)
* Backup status doesnt received at last 6h (trigger)

roadmap
===
* Compatibility with MySQL
* Install script

installation
===
* create a sudo entry to execute script
* copy conf/Bacula.conf to /etc/zabbix/zabbix.agent.d/
* copy scripts/ to /etc/zabbix/scripts

contributors
=====
* Fábio Miguel Mello (me)

