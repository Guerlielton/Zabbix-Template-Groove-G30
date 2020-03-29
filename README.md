# Zabbix-Template Groove G30

Tested from zabbix 4.0.14 

Server Ubuntu 18.04 LTS

It uses SNMPv2

Add Coriant-groove.mib for OID in textual-convention  on /usr/share/snmp/mibs after add files restart service snmpd

Features: 

-ochOsPreFecBer

-OmsTX-RX Optical Power

-Port Tx Rx Optical Power

-Osnr-Table

-Q-Factor-Table

-Shelf-Temperature

-Graph based in items discovery

Requirements:

Coriant-groove.mib
