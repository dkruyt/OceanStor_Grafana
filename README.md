### OceanStor_Grafana

A templated Dashboard for Huawei OceanStor storage (v2/v3) metrics

Dependencies InfluxDB as the time-series database Telegraf as the collector

### Quick Start

* Enable SNMP on your Huawei OceanStor storage
* Put hw_stor.conf in your telegraf.d directory
* Edit the community string as appropriate
* Edit the SNMP verion as appropriate
* Edit the 'agents' list to include all of your monitored OceanStor storages
* Import the Grafana dashboard
