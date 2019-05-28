## Consul to zabbix monitoring
### Consul or zabbix? Both!  
With this template you can easily see consul health checks on zabbix.  
You can register service on consul and see it status on zabbix.  
It provide:
1. Autodetect consul services.
2. Consul health check status to zabbix.
3. Add the URL of the discovered consul service to the host trigger definition (URL and description)
4. Alerts if consul health check fail
5. Report status of consul node



## How to install


``` bash
sudo mkdir /opt/scripts
sudo cp consul2zabbix.py /opt/scripts/
```
change consul address/port to actual value
Import template consul2zabbix.xml to zabbix server. Change severity level.

Add Consul2Zabbix template to nodes on which you want to map consul services to zabbix.
