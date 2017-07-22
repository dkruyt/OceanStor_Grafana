### OceanStor_Grafana

A templated Dashboard for Huawei OceanStor storage (v2/v3) metrics

Dependencies InfluxDB as the time-series database Telegraf as the collector

For all latest files, see [My GitHub page](https://github.com/dkruyt/OceanStor_Grafana)

### Quick Start

* Enable SNMP on your Huawei OceanStor storage
* Put hw_stor.conf in your `/etc/telegraf/telegraf.d` directory
* Edit the community string as appropriate
* Edit the SNMP verion as appropriate, please note that verion 2 is disabled by default on the Huawei OceanStor, check with `show snmp version` on the Storage
* Edit the 'agents' list to include all of your monitored OceanStor storages
* Put the files in the mibs dir `/usr/share/snmp/mibs`
* Import the Grafana dashboard

### Screenshot

After you setup all, you should have some dashboard like this

![Grafana screenshot zswap](https://github.com/dkruyt/OceanStor_Grafana/raw/master/Grafana___Huawei_Storage_edit.jpg)
