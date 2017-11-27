Munin Plugins
=============

EPC3208 Cable modem
-------------------
Wildcard plugin to monitor EPC3208 cable modem by parsing the public web admin interface, 
since the SNMP access is limited to the cable provider.

You probably need to configure a second IP adress on one of your local network adapters in order to reach 
the interface at http://192.168.100.1/

The plugin uses BeautifoulSoup and Python 2. See the script file for more details.

Access Point Statistics
-----------------------
This plugin uses iw <if> station dump to generate statistics of clients connected to the wireless adapter in AP (e.g. with hostapd) mode.

See the script file for more details.

EDAC Memory ECC Error Reporting 
------------------------------- 
The `edac_` plugin uses edac-utils sysfs 
interface to count corrected and uncorrected ECC memory errors for each CS row in the system.
